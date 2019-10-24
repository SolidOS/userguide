---
description: User Guide For Sharing Data Browser view
---

# Sharing View User Guide

- [Introduction](#introduction)
- [View](#view)
- [Specific Sharing for a Resource](#specific-sharing-for-a-resource)
- [Custom Sharing](#custom-sharing)
  - [Add](#add)
  - [Adjust](#adjust)
  - [Remove](#remove)
  
## Introduction
Solid allows you to control who can access folders and data resources within your Pod, and what permission they have — i.e., read, create, update, and/or delete. 

## View
To display the Sharing view for a folder or data resource:
1. In the [Data Browser](https://github.com/solid/userguide/README.md), navigate to the resource.
2. Select the <img src="https://solid.github.io/solid-ui/src/icons/padlock-timbl.svg" alt="Sharing" width="16" > Sharing view.
3. The Sharing settings for the selected resource are displayed:

<img src="Sharing_View.png" alt="Sharing" width="1024" style="border: 1; border-style:solid; border-color: rgb(200,200,200)">

For each of the Sharing groups - Owners, Editors, Posters, Submitters, Viewers, the Sharing view displays the group members and the assigned permissions.

_Tip: Clicking the <img src="https://solid.github.io/solid-ui/src/originalIcons/go-to-this.png" alt="Sharing" width="16"> Goto This icon next to the user's Profile image/name will display the user's profile._

## Specific Sharing for a Resource
By default, resources within a folder inherit the permissions from the parent folder. 

To set specific sharing for the resource:
1. Click the **Set the sharing of folder contents separately from the sharing for the folder** button.
2. This causes the sharing groups (Owners, Editors, Posters, Submitters, Viewers) for the specific resource to be displayed.

To reset the sharing for the resource back to the default:
1. Click the **Stop specific sharing for this folder/file** button.

## Custom Sharing
The sharing permissions for a given resource can be updated to provide access to specific users, groups, bots, authenticated agents, trusted applications, or even everyone.

### Add
To add a user/group/bot as Viewers:
1. Click the <img src="https://solid.github.io/solid-ui/src/icons/noun_34653_green.svg" alt="Add" width="16" > Add icon.
2. Icons are displayed for each of the entities that can be given access to the resource:
    * <img src="https://solid.github.io/solid-ui/src/icons/noun_15059.svg" alt="User URI" width="20" > User.
    * <img src="https://solid.github.io/solid-ui/src/icons/noun_339237.svg" alt="Group URI" width="20" > Group.
    * <img src="https://solid.github.io/solid-ui/src/icons/noun_98053.svg" alt="Everyone" width="20" > Everyone.
    * <img src="https://solid.github.io/solid-ui/src/icons/noun_99101.svg" alt="Authenticated Agent" width="20" > Authenticated Agent.
    * <img src="https://solid.github.io/solid-ui/src/icons/noun_Robot_849764.svg" alt="Bot URI" width="20" > Bot.
    * <img src="https://solid.github.io/solid-ui/src/icons/noun_15177.svg" alt="Trusted Applications" width="20" > Trusted Applications.
3. Select the entity type for which you want to provide access.
    * If a <img src="https://solid.github.io/solid-ui/src/icons/noun_15059.svg" alt="User URI" width="20" > User, <img src="https://solid.github.io/solid-ui/src/icons/noun_339237.svg" alt="Group URI" width="20" > Group or <img src="https://solid.github.io/solid-ui/src/icons/noun_Robot_849764.svg" alt="Bot URI" width="20" > Bot is selected to be added:
        1. A text box is displayed allowing the URI for the entity to be entered.
        2. Enter the URI for the entity and click <img src="https://solid.github.io/solid-ui/src/icons/noun_1180158.svg" alt="Continue" width="20" > Continue.
        3. The entered entity is added as a Viewer.
    * If <img src="https://solid.github.io/solid-ui/src/icons/noun_98053.svg" alt="Everyone" width="20" > Everyone or <img src="https://solid.github.io/solid-ui/src/icons/noun_99101.svg" alt="Authenticated Agent" width="20" > Authenticated Agent is selected:
        1. Everyone or Authenticated Agent is immediately added as a Viewer.
    * If <img src="https://solid.github.io/solid-ui/src/icons/noun_15177.svg" alt="Trusted Applications" width="20" > Trusted Applications is selected:
        1. A list of your trusted applications is displayed.
        2. Select the Trusted Applications you want to give access.
        3. The selected Trusted Applications are added as Viewers.
4. Once added, the sharing access of the entity can be [adjusted](#Adjust).

_Tip: To add a entity to a specific sharing group, drag-and-drop the URI for the entity onto the sharing group._

### Adjust
To move an entity between sharing groups:
1. Click-and-drag the entity between the sharing groups.


### Remove
To remove an entity from a sharing group:
1. Hover the mouse pointer over the <img src="https://solid.github.io/solid-ui/src/originalIcons/go-to-this.png" alt="Goto This" width="16"> Goto This icon next to the user's Profile image/name.
2. A <img src="https://solid.github.io/solid-ui/src/icons/noun_2188_red.svg" alt="Sharing" width="16"> Remove icon is displayed. 
3. Click the <img src="https://solid.github.io/solid-ui/src/icons/noun_2188_red.svg" alt="Sharing" width="16"> Remove icon to remove the sharing access for the entity.
