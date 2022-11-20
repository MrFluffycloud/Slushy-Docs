---
label: Ban & Unban 🔨
layout: default
order: 10
description: Command to Ban a user from the server 🔨!
icon: issue-draft
---

## :icon-dot: Ban Command

> Ban a user from the guild.

!!! Syntax for Slash Command
**/ban [!badge variant="dark" text="<span style='color:red;'>\*</span> user"] [!badge variant="dark" text="<span style='color:red;'>\*</span> reason"] [!badge variant="dark" text="time"] [!badge variant="dark" text="proof"]**

**Note:** Any parameter prefixed with <span style='color:red;'>\*</span> is required, the others are optional.

!!!

### :icon-quote: Fields

| Indicator      | Statuses { class="compact" }                                                                                                                                                                                            |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 📥 DMed        | **✅ Successful**: The user was successfully DMed about his removal from the guild</br>**❌ Failed**: Was unable to Dm the user, probably due to DMs being closed or the user not being in any mutal server with Slushy |
| ⌚ Time        | **Time the user is banned for.**</br>Field is ignored if its a permanant ban                                                                                                                                            |
| 🖼️ Proof Image | Attaches the Image with the embed if any proof is provided.                                                                                                                                                             |

### :icon-apps: Parameters

| Parameter | Description                                                                                                                                               | Examples                                                                                                                                                                                               |
| :-------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| user      | A User, It is the user that you want to ban, Can be a Member or a User who isn't in the guild.</br>You can input either the user id or even mention them! | - `/ban user:676745968867082250 reason:example`</br>Bans user with id `676745968867082250`</br>- `/ban user:@MrFluffyCloud#9999 reason:example`</br>Bans user mentioned, which is `MrFluffyCloud#9999` |
| reason    | A String, The reason for banning the user, it's necessary for the staff team members to add this for Security reasons                                     | - `/ban user:@MrFluffyCloud#9999 reason:example`</br>Bans user with id `676745968867082250` with reason `example`                                                                                      |
| time      | A String, If you'd like to temporarily ban the user, you may input a time in ss mm hh dd format                                                           | - `/ban user:@MrFluffyCloud#9999 reason:example time:1d`</br>>Bans user mentioned, which is `MrFluffyCloud#9999` for `1 Day`                                                                           |
| proof     | A Attachment, Proof for the reason for the ban, not necessary but good if you add it along                                                                | - `/ban user:@MrFluffyCloud#9999 reason:example proof:<file>`</br>>Bans user mentioned, which is `MrFluffyCloud#9999` along with the proof in \<file\>                                                 |

### :icon-eye: Output

![Preview: `/ban user:@MrFluffycloud#9999 reason:Test time:10days proof:<file>`](/static/sample.jpg)

## :icon-dot: Unban Command

> Unban a banned user from the guild.

!!! Syntax for Slash Command
**/ban [!badge variant="dark" text="<span style='color:red;'>\*</span> user"] [!badge variant="dark" text="<span style='color:red;'>\*</span> reason"]**

**Note:** Any parameter prefixed with <span style='color:red;'>\*</span> is required, the others are optional.

!!!

### :icon-apps: Parameters

| Parameter | Description                                                                                                             | Examples                                                                                                                                                                                                                             |
| :-------- | :---------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| user      | A User, It is the user that you want to unban.</br>You can input either the user id or even mention them!               | - `/unban user:676745968867082250 reason:example`</br>Unbans the banned user with id `676745968867082250`</br>- `/unban user:@MrFluffyCloud#9999 reason:example`</br>Unbans the banned user mentioned, which is `MrFluffyCloud#9999` |
| reason    | A String, The reason for unbanning the user, it's necessary for the staff team members to add this for Security reasons | - `/unban user:@MrFluffyCloud#9999 reason:example`</br>Unbans the banned user with tag `MrFluffyCloud#9999` with reason for unban being `example`                                                                                    |     |
