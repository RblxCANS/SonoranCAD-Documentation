---
description: This endpoint allows you to detach a unit from any active dispatch call.
---

# Detach Unit



{% hint style="warning" %}
This API endpoint requires the **plus** version of Sonoran CAD or higher. For more information, see our [pricing ](../../../../pricing/faq/)page.
{% endhint %}

{% hint style="info" %}
Detaching units via the API does not send an [EVENT\_UNIT\_DETACH ](../../push-events/dispatch-events/detach-unit.md)push event. These events should be listened to locally on the game server.
{% endhint %}

{% api-method method="post" host="https://api.sonorancad.com" path="/emergency/detach\_unit" %}
{% api-method-summary %}
Detach Unit
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to attach new units to an existing dispatch call.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="id" type="string" required=true %}
Your community's ID
{% endapi-method-parameter %}

{% api-method-parameter name="key" type="string" required=true %}
Your community's API Key
{% endapi-method-parameter %}

{% api-method-parameter name="type" type="string" required=true %}
DETACH\_UNIT
{% endapi-method-parameter %}

{% api-method-parameter name="data" type="array" required=true %}
Array of request objects
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
A successful call will be met with the following response:
{% endapi-method-response-example-description %}

```
UNITS DETACHED
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}
The following 400 errors may be sent in response:
{% endapi-method-response-example-description %}

```http
INVALID REQUEST TYPE
INVALID COMMUNITY ID
API IS NOT ENABLED FOR THIS COMMUNITY
INVALID API KEY
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

```javascript
{
    "id": "YOUR_COMMUNITY_ID",
    "key": "YOUR_API_KEY",
    "type": "DETACH_UNIT",
    "data": [
        {
            "serverId": 1, // Default 1 - See guide on setting up multiple servers
            "units": ["STEAN:1234"] // Array of API IDs
                                // Typically, this is their STEAM Hex
        },
    ]
}
```

