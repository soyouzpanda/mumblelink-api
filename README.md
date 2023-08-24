# Documentation for Mumble Link Core

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://localhost*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *DefaultApi* | [**serverServerIdDelete**](Apis/DefaultApi.md#serverserveriddelete) | **DELETE** /server/{server_id} |  |
*DefaultApi* | [**serverServerIdGet**](Apis/DefaultApi.md#serverserveridget) | **GET** /server/{server_id} |  |
*DefaultApi* | [**serverServerIdUserUserIdGet**](Apis/DefaultApi.md#serverserveriduseruseridget) | **GET** /server/{server_id}/user/{user_id} |  |
*DefaultApi* | [**serverServerIdUserUserIdMutePost**](Apis/DefaultApi.md#serverserveriduseruseridmutepost) | **POST** /server/{server_id}/user/{user_id}/mute |  |
*DefaultApi* | [**serverServerIdUserUserIdUnmutePost**](Apis/DefaultApi.md#serverserveriduseruseridunmutepost) | **POST** /server/{server_id}/user/{user_id}/unmute |  |
*DefaultApi* | [**serverServerIdUsersGet**](Apis/DefaultApi.md#serverserveridusersget) | **GET** /server/{server_id}/users |  |
*DefaultApi* | [**serversCreatePost**](Apis/DefaultApi.md#serverscreatepost) | **POST** /servers/create | Create a new server |
*DefaultApi* | [**serversGet**](Apis/DefaultApi.md#serversget) | **GET** /servers | Get list of servers |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Error](./Models/Error.md)
 - [ServerInfo](./Models/ServerInfo.md)
 - [UserInfo](./Models/UserInfo.md)
 - [_server__server_id__users_get_200_response](./Models/_server__server_id__users_get_200_response.md)
 - [_servers_create_post_request](./Models/_servers_create_post_request.md)
 - [_servers_get_200_response](./Models/_servers_get_200_response.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="Bearer"></a>
### Bearer

- **Type**: HTTP basic authentication

