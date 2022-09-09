# Tealium Data Visualizer

The TDV is a Chrome extension that helps show events and visitor stitching during demos. 👀

## Installation

The TDV requires Chrome and is installed by sideloading.
- Download the zip [file](https://drive.google.com/file/d/11031amvWZy03O5Y5sQ1T7mk32Kr2ecEx/view?usp=sharing)
- Unzip the tdv_alpha_0.1.zip folder
- Open Chrome extensions
- Toggle on "Developer mode" (found in upper-right corner)
- Select "Load unpacked"
- Select the unzipped folder "tdv_alpha_0.1"
- You're all set 🤙

## Getting Started

In order to use the tool, sign in to Tealium first either by SSO or by email. (You can also sign in within the Tool, but this is still in beta.) Then go to a site that has a Tealium script (either hard-coded or via TamperMonkey) on the page and open the tool. 

## Trace Setup

The first field is a "Profile" dropdown. The tool will pick up on all the collect endpoints that are associated to this profile, and you need to select which to work off of. (The tool will also work with the Environment Switcher Tealium Tool.)

In the "Setup" tab and in the "Trace Setup" section, selecting the "Start" button will start a trace. There is no need to add the trace ID in the AudienceStream Trace Tealium Tool as this is done automatically.

## Creating Milestones

Milestones are like filters for events or attributes that you want to listen to when trace is on. When creating a milestone, you will select what type it is and then filter down until you select the specific audience/badge/event feed/action you want.

## Viewing Trace

After turning trace on and creating milestones, go to the "Trace" tab and you will see the milestones you have preconfigured come through (as long as those milestones are met).

## Visitor Profile 

The vistor profile section is found in the top part of the "Trace" tab and notes the three states of a visitor: "New", "Returning", or "Known".

## Notes

The extension is currently in alpha, so we are still working out some kinks. Please keep in mind a few things:
- If consent is not given, the profile dropdown will not populate.
- When signing in to Tealium first, open the tool within that same window.

## Troubleshooting and Support

Please slack #sc_ops for support or feedback! 🙏
