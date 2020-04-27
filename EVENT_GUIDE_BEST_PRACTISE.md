# VR Events on Mozilla Hubs

On April 6th the IOTA Community organized the first VR IOTA Meetup on the [Mozilla Hubs](http://hubs.mozilla.com) platform.
This document summarizes general feedback and best practices collected through this experience.

## What is Mozilla Hubs

[Hubs](https://hubs.mozilla.com/docs/welcome.html) is for anyone who wants to connect with others remotely! It's a great way to bring communities together in a virtual space. Host a conference, teach a class, create art, or just hang out with friends. Because of Hubs' spatialized audio you can have conversations with everyone together or break out into smaller groups, just like you can in person.

- Key Features
- Works across platforms
- Customizable scenes and avatars
- Self-hosting options available
- Built with [privacy](https://blog.mozvr.com/creating-privacy-centric-virtual-spaces/) in mind

## Setup

Mozilla Hubs are [privacy centric](https://blog.mozvr.com/creating-privacy-centric-virtual-spaces/) virtual spaces. The [code is open source](https://github.com/mozilla/hubs) and the platform can be self hosted [Hubs Cloud](https://hubs.mozilla.com/docs/hubs-cloud-intro.html) on [AWS](https://hubs.mozilla.com/docs/hubs-cloud-aws-quick-start.html) ([estimated costs](https://hubs.mozilla.com/docs/hubs-cloud-aws-costs.html)).

Mozilla Hubs make it possible to join the VR rooms without registration, using any device like a PC or Smartphone through the browser, with or without VR gear ([supported devices](https://hubs.mozilla.com/docs/hubs-create-join-rooms.html#supported-devices--browsers)). For best performance and overall experience on low end devices, the Mozilla team suggests a limit in the number of guests per room to 24/25.

## Public Rooms and security

For the first event the organizers leveraged public rooms made available by Mozilla Hubs to keep a lower entry barrier.The free platform does not have an administrative panel nor an easy management tool, therefore the team had to get creative (more about administration and security later in the document). This is not an issue when the hubs are shared with trusted parties, although anonymity and public events can bring to certain issues; see [zoom-bombing](https://www.theverge.com/2020/4/3/21207260/zoombombing-crime-zoom-video-conference-hacking-pranks-doj-fbi).

## Custom VR scene

![img](https://lh3.googleusercontent.com/OOYIFVBV_7lI333SbxjavcF7fxTONiQcZdzK8ULg39He2D_p97wS9P4hrqijPoOaBGBUeRQblUDHASP3GaO7UseTzMGgYBusqb97tfi7hsVrFUkYQifW_ay7sAz0wsoM1HN360nX)

Using Spoke two customized scenes are set up, [available here](https://github.com/iota-community/IOTA-VR-events-mozilla-hub). To achieve this goal a template by Mozilla is adapted to save time.
The room has two spawn points in the far back. This adaptation helps the moderation in the rooms, as a "doorman" can quickly recognize a malicious participant and kick him from the room, before disruption can happen.
On the left hand side are tables and a screen. The screen shows a looping YouTube video from a past meetup. This video is chosen to give a feeling of meeting people in real life and evoke "familiarity and humanity" in the digital space.
The front is called **Forum** or **Main stage**. In this location the moderation and presentations take place.
To reach the forum the left and right hand side have billboards and screens at eye level.The billboards are used to publicize latest news and organizers sponsors.
The screens at eye level have links to blog posts or websites that will open in the users browser.

## Rooms

One room is set up as **speakers and organizers room (SOR)**. In this room the moderation, presentations and video streaming to youtube take place. The link to the **SOR** was shared only between identified parties to avoid interruption or disruption of the presentations or the ban of the streamer’s youtube account through actions by malicious parties.
Six other rooms are set up as **guest rooms**. The YouTube livestream of the SOR is shared to the screen in the Forum of the **guest rooms**. 

The difference between the two scenes are:

- The screen in the Forum area of the SOR is left blank
- The room settings in the guest rooms are limited to minimize confusion and performance loss

![img](https://lh5.googleusercontent.com/0vQciY_3-VWPTGrPbCab2A2gn-aScvJGHEfoj_sKdBuL3WldcRYBv1CsqzNQULyg6ilUlfH_IXxg-rJKvSjYiMWvz3uesd3hM0yWdTPXPHKgOdZ61i54qOMPkHWtIkrLsrKbmJbx)

## Workflow

Usual event workflow. In the case of an event with public links, it might be helpful to find people that will support the event as moderators, to kick malicious actors, support users and close a room in the worst case scenario.
It is suggested to use a [self hosted](https://hubs.mozilla.com/docs/hubs-cloud-aws-quick-start.html) Hub to have more control over the platform and an administrative panel.
A suggestion for the Host/Speakers: if desired it is possible to share the webcam and show themselves before showing a presentation, to make a connection between the avatar and the person.

# Administration and Security

## Hubs cloud

![img](https://lh6.googleusercontent.com/GFcrehZu_Tkk2OEraCF3sPo13fTbj3mkVXanERhdDSxbwXl-HAjiEaXK8e0U7yaejsL2UZYkEpCg9avp6U1iNfA45-apnyz4tMfxJQAOSRM2hmd9iaCpYR3iEhEToQpRl6w_5i5p)

Administration tools are **only** available for self hosted [Hubs Cloud](https://hubs.mozilla.com/docs/hubs-cloud-intro.html) on [AWS](https://hubs.mozilla.com/docs/hubs-cloud-aws-quick-start.html) ([estimated costs](https://hubs.mozilla.com/docs/hubs-cloud-aws-costs.html)).Here's some things you can do to continue setting up your hub:

- [Import content](https://hubs.mozilla.com/docs/hubs-cloud-importing-content.html) so your visitors will have access to a library of scenes and avatars.
- [Customize the Look and Feel](https://hubs.mozilla.com/docs/hubs-cloud-customizing-look-and-feel.html) to make your hub fit your brand or style.
- [Enable the Scene Editor](https://hubs.mozilla.com/docs/hubs-cloud-enable-scene-editor.html) to let visitors create their own scenes.
- [Enable permissive rooms](https://hubs.mozilla.com/docs/hubs-cloud-permissive-rooms.html) to let visitors add media to their rooms.
- [Set up the media browser](https://hubs.mozilla.com/docs/hubs-cloud-enable-media-browser.html) so visitors can add content from sites like Sketchfab and Google Poly.
- [Learn how to manage content](https://hubs.mozilla.com/docs/hubs-cloud-managing-content.html) so visitors can contribute content to your hub.
- [Add Administrators](https://hubs.mozilla.com/docs/hubs-cloud-adding-administrators.html) if you'd like others to help you set up your hub.

## Hubs Discord bot

The [Hubs Discord bot](https://hubs.mozilla.com/docs/hubs-discord-bot.html) makes it easy to connect Hubs rooms to your Discord chat server. When a Hubs room is associated with a Discord channel, users will be assigned abilities in the Hubs room based on their Discord roles. For example, Discord owners and moderators will be able to change settings on a Hubs room and be able to moderate users in the room

#### Key Features

- Allows you to authenticate users joining your Hubs room
- Saves a record of photos and text chat created in Hubs
- Posts in the Discord channel when someone joins or leaves the Hubs room

## Security

Security has a price in usability and ease of use, although security for the event participants, speakers and organizers should be the focus when organizing such events.

Participation possibilities (sorted by most secure):

- **Easy** - Register on Eventbrite/Meetup and watch the YouTube stream

- **Pro** - Register on Eventbrite/Meetup, register on the Discord server, access Mozilla Hubs through Discord, join the Mozilla Hub using VR gear

  **Hard** - Register on Eventbrite/Meetup, register on the Discord server, access Mozilla Hubs through Discord, join the Mozilla Hub using a PC/smartphone through the browser

- **Normal** - Register on Eventbrite/Meetup, join the Mozilla Hub using a PC/smartphone through the browser

The safest way to participate in an online VR event is to passively watch the video stream on YouTube. As seen later in the document a separate room for the organizers, speakers and streamers is set up, therefore disruption possibilities are lowered to a minimum, unless one of these participants makes the link publicly available.
The next way to participate and to make the event safe to participate is to have control over the people that can access the event. In this regard access control through a Discord server and a team of moderators is necessary. To support your moderators in the decision making process a Code of Conduct for events should be enforced and communicated to the participants (e.g. [CoC Linux Foundation](https://events.linuxfoundation.org/about/code-of-conduct/)).

## Participants

Use a platform like Eventbrite or Meetup for participants' registrations.
Inform the participants that Mozilla Hubs will be used to prepare themselves for the experience, familiarize with the platform, with the [controls](https://hubs.mozilla.com/docs/hubs-controls.html), verify [if their devices are supported](https://hubs.mozilla.com/docs/hubs-create-join-rooms.html#supported-devices--browsers).

Participation possibilities (sorted by entry barrier):

- **Easy** - Register on Eventbrite/Meetup and watch the YouTube stream
- **Normal** - Register on Eventbrite/Meetup, join the Mozilla Hub using a PC/smartphone through the browser
- **Hard** - Register on Eventbrite/Meetup, register on the Discord server, access Mozilla Hubs through Discord, join the Mozilla Hub using a PC/smartphone through the browser
- **Pro** - Register on Eventbrite/Meetup, register on the Discord server, access Mozilla Hubs through Discord, join the Mozilla Hub using VR gear

Accept to follow the Code of Conduct.

## YouTube stream

Set up a secondary Mozilla Hubs account and avatar for the **Streamer** to record the event and stream it live to YouTube. Set this account as moderator. This user should be skilled to freely move in the room and position himself dynamically to support the speakers and organizers.

## Scene customization

Customize scene(s), by updating YouTube video links and the live stream link, billboard images and screen links. Actual scenes are available on GitHub here: https://github.com/iota-community/IOTA-VR-events-mozilla-hub

## Room creation

Open the SOR and apply the custom SOR scene.

Open the necessary number of guest rooms, apply the custom scene and set restrictive room settings. The number of guest rooms equals to the number of confirmed guests divided by 25.Bookmark the link to every room for faster management should you need to adapt the links to the livestream or change scenes.
If you are using public rooms, invite identified participants together in rooms and use one or two specific rooms for unidentified/less known/anonymous participants; be prepared to close these rooms in worst case scenarios.

## Best practices

### Organizers

- Get familiar with:
  - The Mozilla Hubs platform in general ([documentation](https://hubs.mozilla.com/docs/welcome.html))
  - Room specific settings
  - Spoke to update links and billboard images
  - With the custom room
  - First person view
  - [Avatar movements/controls](https://hubs.mozilla.com/docs/hubs-controls.html)
  - Setting up webcam/screen sharing
  - Utilizing objects in the VR scene
- Have a team of moderators for Discord and Mozilla Hubs
- Setup and thoroughly test
  - Personal audio and video equipment
  - Youtube streaming capabilities
- Organize rehearsals for the speakers and moderators
- Find an easy way to manage the rooms and to quickly update scenes
- Create a Code of Conduct for events and inform every participant about it (e.g. [CoC Linux Foundation](https://events.linuxfoundation.org/about/code-of-conduct/)).
- The CoC is also a supporting guide for taking decision in the moderation/kick/bans of participants
- If possible
  - Use a Discord server with the participants
  - Use the [Discord Bot](https://hubs.mozilla.com/discord) to manage access to the rooms
  - Self-host the event to leverage administration tools
  - Set up a secondary communication channel (Discord server, Slack, Telegram) to communicate with the speakers
  - Set up a secondary communication channel (Discord server, Slack, Telegram) to communicate with the moderators
  - Invite identified participants together in rooms
  - Use one or two specific rooms for unidentified/less known/anonymous participants with more than one participant and be prepared to close these rooms in worst case scenarios

### Speakers/Host

- Get familiar with:
  - The Mozilla Hubs platform in general ([documentation](https://hubs.mozilla.com/docs/welcome.html))
  - With the custom room
  - First person view
  - [Avatar movements/controls](https://hubs.mozilla.com/docs/hubs-controls.html)
  - Setting up webcam/screen sharing
  - Utilizing objects in the VR scene
- Setup and thoroughly test personal audio and video equipment
- Rehearse the presentation in the Hub with screen sharing and screen object setup
- Start the presentation by sharing the webcam and showing yourself
- Move close to the Streamer to insure a higher sound quality

### Streamer

- Get familiar with:
  - The Mozilla Hubs platform in general ([documentation](https://hubs.mozilla.com/docs/welcome.html))
  - Spoke to update links and billboard images
  - With the custom room
  - First person view
  - [Avatar movements/controls](https://hubs.mozilla.com/docs/hubs-controls.html)
  - Setting up webcam/screen sharing
  - Utilizing objects in the VR scene
- Setup and thoroughly test
  - personal audio and video equipment
  - OBS
  - Youtube streaming capabilities
- To hide the user interface when recording, you can press the tilde key (~), or turn on [camera mode](https://hubs.mozilla.com/docs/hubs-room-settings.html#camera-mode).
- Actively follow the presentations
- Use two screens, one to see the YouTube stream, one with the hubs, to adjust position, sound recording quality

### Moderators

- Get familiar with:
  - The Mozilla Hubs platform in general ([documentation](https://hubs.mozilla.com/docs/welcome.html))
  - With the custom room
  - First person view
  - [Avatar movements/controls](https://hubs.mozilla.com/docs/hubs-controls.html)
  - Setting up webcam/screen sharing
  - Utilizing objects in the VR scene
  - Room settings
    ![img](https://lh4.googleusercontent.com/YMcy7_5_eIcdgY80cuNxoUtPYACzmR5wOcmY5NSjB6dzI-HF63nhUF4WvCeDAQSPgL3bhfVkHtdcgTV9K3AxMuYGVCpyTTxDerJvQvG5fb9FZEzx4KCRIuYbim1bSaCBkz2vb9nE)
  - User kick function and administrative tools
  - Discord moderation settings to add/remove user roles
- Setup and thoroughly test personal audio and video equipment
- Join rehearsals for the speakers and moderators
- Find an easy way to manage the rooms and to quickly update scenes
- Be aware of the Code of Conduct
- Use the CoC as a supporting guide for taking decision in the moderation/kick/bans of participants

## Useful links

- Mozilla Hubs
  [https://hubs.mozilla.com/](https://hubs.mozilla.com/docs)
- Spoke
  https://hubs.mozilla.com/spoke/Hozilla
- Hubs documentation
  https://hubs.mozilla.com/docsMozilla
- Hubs troubleshooting
  https://hubs.mozilla.com/docs/hubs-troubleshooting.htmlMozilla
- Hubs FAQ
  https://hubs.mozilla.com/docs/hubs-faq.htmlMozilla
- Hubs Discord bot
  https://hubs.mozilla.com/docs/hubs-discord-bot.html

## Glossary

- **Mozilla Hubs** = Online platform for VR virtual spaces
- **Spoke** = Online 3D scene editor on the Mozilla Hubs platform
- **Room** = Virtual room, virtual space or channel
- **Scene** = Customizable appearance of a virtual world inside a room, these can be edited in Spoke
- **Avatar** = graphical 3D representation of the user or the user's alter ego or character
- **Spawn Point** = Point in the VR space, where people enter the location with their avatar
- **FPV** = First person view, the user sees from the “eyes of the avatar”
- **Moderator** = User that has more controls over the rooms, like kick people and change settings
- **Streamer** = User that uses a broadcasting tool like [OBS](https://obsproject.com/) to stream the event to the YouTube account
- **Hubs Cloud** = Self hosted Mozilla Hubs instance
- **Discord** = Text and Voice chat application
