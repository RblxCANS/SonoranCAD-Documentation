---
description: Learn more about our Roblox integration with CGVRP!
---

# 🎮 Roblox CGVRP

                                                             ![Sonoran CAD x CGVRP]

{% hint style="warning" %}
These **** features utilize API endpoints that require the **standard** version of Sonoran CAD or higher. You can view the specific version requirements [listed under each feature](roblox-CGVRP.md#in-game-commands-and-features), or [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

## What is CGVRP?
CGVRP is a fun, Roblox based, roleplay server. We are mainlyfocused on a game called Greenville which is a driving game

We're excited to support the following in-game integration options with ER:LC

* Live unit locations
* Traffic stop 
* In-game plate search
* In-game name search
* Panic command
* Automated emergency calls for fires and robberies
* In-game 911 calls sent to Sonoran CAD
* and more!

## Getting Started

### Unit Locations

{% hint style="warning" %}
This feature utilizes API endpoints that require the **standard** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

Once you have [added your Roblox API ID](roblox-cgvrp.md#for-community-members) to the CAD, your unit location in-game will be updated as you move around the map.

![Sonoran CAD - Unit Locations](<../.gitbook/assets/Screen Shot 2021-11-27 at 10.17.54 AM.png>)

### Plate Search

{% hint style="warning" %}
This feature utilizes API endpoints that require the **plus** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

| Command                | Description        |
| ---------------------- | ------------------ |
| `/sp <plate>`          | Run a plate search |
| `/searchplate <plate>` | Run a plate search |

Ex: `/sp abc1234`

Once you have [added your Roblox API ID](roblox-cgvrp.md#for-community-members) to the CAD, running a pate search in-game will automatically pop up the results on your CAD screen.

![Sonoran CAD: Plate Search](<../.gitbook/assets/Screen Shot 2021-11-27 at 10.24.49 AM.png>)

### Name Search

{% hint style="warning" %}
This feature utilizes API endpoints that require the **plus** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

| Command              |                   |
| -------------------- | ----------------- |
| `/sn <name>`         | Run a name lookup |
| `/searchname <name>` | Run a name lookup |

Ex: `/sn Brian Sauce`

Once you have [added your Roblox API ID](roblox-cgvrp.md#for-community-members) to the CAD,  running a name search in-game will automatically pop up the results on your CAD screen.

![Sonoran CAD: Name Search](<../.gitbook/assets/Screen Shot 2021-11-27 at 10.25.04 AM.png>)

### Traffic Stop

{% hint style="warning" %}
This feature utilizes API endpoints that require the **plus** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

| Command               | Description                                          |
| --------------------- | ---------------------------------------------------- |
| `/ts <info>`          | Creates and attaches you to a traffic stop dispatch  |
| `/trafficstop <info>` | Creates and attaches you to a traffic stop dispatch  |

Ex: `/ts Red Tahoe, ABC123`

Once you have [added your Roblox API ID](roblox-cgvrp.md#for-community-members) to the CAD, running the traffic stop command will automatically create and attach you to a new dispatch call with your information.

Note: Don't include your location in the traffic stop info, the command will automatically add this to the call.

![Sonoran CAD: Traffic Stop Dispatch](<../.gitbook/assets/Screen Shot 2021-11-27 at 10.36.11 AM.png>)

### 911 Calls

{% hint style="warning" %}
This feature utilizes API endpoints that require the **standard** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

| Command           | Description                                 |
| ----------------- | ------------------------------------------- |
| `/setname <name>` | Sets a roleplay name used when calling 911. |

Using your cell phone in-game, you can call emergency services. This 911 call will be sent directly to Sonoran CAD.

### Automated Alarms

{% hint style="warning" %}
This feature utilizes API endpoints that require the **plus** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

Automated alarms from fire alarms or robberies will also be automatically sent to the CAD's emergency call section.

### Panic

{% hint style="warning" %}
This feature utilizes API endpoints that require the **standard** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

| Command  | Description                      |
| -------- | -------------------------------- |
| `/panic` | Toggles your unit's panic status |

Additionally, you can also use the desktop application's [panic hotkey](../tutorials/other-features/configurable-hotkeys.md).

## Auto-Complete Street Addresses

{% hint style="warning" %}
This feature utilizes API endpoints that require the **plus** version of Sonoran CAD or higher.

Please [view our pricing page](../pricing/faq/) for more information.
{% endhint %}

Sonoran CAD allows you to import the street addresses from your game to auto-complete in new dispatch calls, custom reports, and more!

We've [created a list](https://docs.google.com/spreadsheets/u/1/d/1jDUxfCffxyGHoXQ-rpzrWRNFEhDmMs3-TA9U-mdNBjg/copy) specifically for ER:LC! [Learn more about importing these street addresses](roblox-er-lc.md#undefined).

![](../.gitbook/assets/addresses.gif)

**THIS IS ONLY IN CGVRP NOT OGVRP OR ANY GREENVILE ROLPEPLAY SERVERS***


