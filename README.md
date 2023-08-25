# Documentation for Mumble Link API

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://localhost*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *DefaultApi* | [**serverCreatePost**](Apis/DefaultApi.md#servercreatepost) | **POST** /server/create | Create a new server |
*DefaultApi* | [**serverServerIdChannelChannelIdDelete**](Apis/DefaultApi.md#serverserveridchannelchanneliddelete) | **DELETE** /server/{server_id}/channel/{channel_id} | Delete a channel |
*DefaultApi* | [**serverServerIdChannelChannelIdGet**](Apis/DefaultApi.md#serverserveridchannelchannelidget) | **GET** /server/{server_id}/channel/{channel_id} | Get channel info |
*DefaultApi* | [**serverServerIdChannelChannelIdPut**](Apis/DefaultApi.md#serverserveridchannelchannelidput) | **PUT** /server/{server_id}/channel/{channel_id} | Modify channel parameters |
*DefaultApi* | [**serverServerIdChannelCreatePost**](Apis/DefaultApi.md#serverserveridchannelcreatepost) | **POST** /server/{server_id}/channel/create | Create a new channel |
*DefaultApi* | [**serverServerIdChannelsGet**](Apis/DefaultApi.md#serverserveridchannelsget) | **GET** /server/{server_id}/channels | Get list of channels |
*DefaultApi* | [**serverServerIdDelete**](Apis/DefaultApi.md#serverserveriddelete) | **DELETE** /server/{server_id} | Delete a server |
*DefaultApi* | [**serverServerIdGet**](Apis/DefaultApi.md#serverserveridget) | **GET** /server/{server_id} | Get server info |
*DefaultApi* | [**serverServerIdGroupCreatePost**](Apis/DefaultApi.md#serverserveridgroupcreatepost) | **POST** /server/{server_id}/group/create | Create a new group |
*DefaultApi* | [**serverServerIdGroupGroupIdDelete**](Apis/DefaultApi.md#serverserveridgroupgroupiddelete) | **DELETE** /server/{server_id}/group/{group_id} | Delete a group |
*DefaultApi* | [**serverServerIdGroupGroupIdGet**](Apis/DefaultApi.md#serverserveridgroupgroupidget) | **GET** /server/{server_id}/group/{group_id} | Get group info |
*DefaultApi* | [**serverServerIdGroupGroupIdPut**](Apis/DefaultApi.md#serverserveridgroupgroupidput) | **PUT** /server/{server_id}/group/{group_id} | Modify group parameters |
*DefaultApi* | [**serverServerIdGroupsGet**](Apis/DefaultApi.md#serverserveridgroupsget) | **GET** /server/{server_id}/groups | Get list of groups |
*DefaultApi* | [**serverServerIdPut**](Apis/DefaultApi.md#serverserveridput) | **PUT** /server/{server_id} | Modify server parameters |
*DefaultApi* | [**serverServerIdUserUserIdBanPost**](Apis/DefaultApi.md#serverserveriduseruseridbanpost) | **POST** /server/{server_id}/user/{user_id}/ban | Ban a user |
*DefaultApi* | [**serverServerIdUserUserIdBansGet**](Apis/DefaultApi.md#serverserveriduseruseridbansget) | **GET** /server/{server_id}/user/{user_id}/bans | Get list of banned users |
*DefaultApi* | [**serverServerIdUserUserIdGet**](Apis/DefaultApi.md#serverserveriduseruseridget) | **GET** /server/{server_id}/user/{user_id} | Get user info |
*DefaultApi* | [**serverServerIdUserUserIdKickPost**](Apis/DefaultApi.md#serverserveriduseruseridkickpost) | **POST** /server/{server_id}/user/{user_id}/kick | Kick a user |
*DefaultApi* | [**serverServerIdUserUserIdMovePost**](Apis/DefaultApi.md#serverserveriduseruseridmovepost) | **POST** /server/{server_id}/user/{user_id}/move | Move a user to another channel |
*DefaultApi* | [**serverServerIdUserUserIdMutePost**](Apis/DefaultApi.md#serverserveriduseruseridmutepost) | **POST** /server/{server_id}/user/{user_id}/mute | Mute a user |
*DefaultApi* | [**serverServerIdUserUserIdUnmutePost**](Apis/DefaultApi.md#serverserveriduseruseridunmutepost) | **POST** /server/{server_id}/user/{user_id}/unmute | Unmute a user |
*DefaultApi* | [**serverServerIdUsersGet**](Apis/DefaultApi.md#serverserveridusersget) | **GET** /server/{server_id}/users | Get list of connected users |
*DefaultApi* | [**serversGet**](Apis/DefaultApi.md#serversget) | **GET** /servers | Get list of servers |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Channel](./Models/Channel.md)
 - [Error](./Models/Error.md)
 - [Group](./Models/Group.md)
 - [Server](./Models/Server.md)
 - [User](./Models/User.md)
 - [_server__server_id__channel__channel_id__put_request](./Models/_server__server_id__channel__channel_id__put_request.md)
 - [_server__server_id__channel_create_post_request](./Models/_server__server_id__channel_create_post_request.md)
 - [_server__server_id__group__group_id__put_request](./Models/_server__server_id__group__group_id__put_request.md)
 - [_server__server_id__group_create_post_request](./Models/_server__server_id__group_create_post_request.md)
 - [_server__server_id__put_request](./Models/_server__server_id__put_request.md)
 - [_server__server_id__user__user_id__ban_post_request](./Models/_server__server_id__user__user_id__ban_post_request.md)
 - [_server__server_id__user__user_id__kick_post_request](./Models/_server__server_id__user__user_id__kick_post_request.md)
 - [_server__server_id__user__user_id__move_post_request](./Models/_server__server_id__user__user_id__move_post_request.md)
 - [_server__server_id__users_get_200_response](./Models/_server__server_id__users_get_200_response.md)
 - [_server_create_post_request](./Models/_server_create_post_request.md)
 - [_servers_get_200_response](./Models/_servers_get_200_response.md)
 - [actions](./Models/actions.md)
 - [ban](./Models/ban.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="Bearer"></a>
### Bearer

- **Type**: HTTP basic authentication

