### Table of Contents
- [home](index.md)
- [admin (feature category)](admin.md)

<br><br><br><br>


# Admin (feature category)

### Content
- [admin moderation](#admin-moderation)
- [editConfig](#editConfig)
- [displayConfig](#displayConfig)
- [resetConfig](#resetConfig)
- [welcomeMsgChat](#welcomeMsgChat)
- [leaveMsgChat](#leaveMsgChat)
- [createTicketPanel](#createTicketPanel)
- [announcmentMsg](#announcmentMsg)

<br><br>

## __admin moderation__
```
%kick @mention
```
Kick a user from the guild.
<br><br>
```
%ban @mention
```
Ban a user from the guild.
<br><br>
```
%unban user_id
```
Unban a user from the guild.
<br><br>
```
%listbans
```
List all bans from the current guild.
<br><br><br><br>
## __editConfif__
```
%editConfig fncCategory=True/False
```
Edit and configure the config file of the current guild.
<br><br><br><br>
## __displayConfig__
```
%displayConfig
```
Displays the guilds config.
So it looks like this:
```
('welcomeMsg', True)
('welcomeMsg_channel', '###################')
('leaveMsg', False)
('leaveMsg_channel', '###################')
('ticketSystem', True)
('announcmentMsg', True)
('levelSystem', False)
('fun', True)
('wiki', False)
('admin', True)
```
<br><br><br><br>
## __resetConfig__
```
%resetConfig
```
Reset the config to the default values.
So it looks like this:
```
('welcomeMsg', false)
('welcomeMsg_channel', '')
('leaveMsg', false)
('leaveMsg_channel', '')
('ticketSystem', false)
('announcmentMsg', false)
('levelSystem', false)
('fun', false)
('wiki', false)
('admin', false)
```
<br><br><br><br>
## __welcomeMsgChat__
```
%welcomeMsgChat channel_id
```
Select a channel to send the embed welcome message.
<br><br><br><br>
## __leaveMsgChat__
```
%leaveMsgChat channel_id
```
Select a channel to send the embed leave messages.
<br><br><br><br>
## __createTicektPanel__
```
%createTicketPanel channel_id; title, description
```
Create a embed message with buttons to greate a ticket 
<br><br><br><br>
## __announcment__
```
%ann channel_id; @mention or False; title; description
```
Send Embed annoucment messages to the channels of your liking.
<br>