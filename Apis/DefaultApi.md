# DefaultApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**serverCreatePost**](DefaultApi.md#serverCreatePost) | **POST** /server/create | Create a new server |
| [**serverServerIdChannelChannelIdDelete**](DefaultApi.md#serverServerIdChannelChannelIdDelete) | **DELETE** /server/{server_id}/channel/{channel_id} |  |
| [**serverServerIdChannelChannelIdGet**](DefaultApi.md#serverServerIdChannelChannelIdGet) | **GET** /server/{server_id}/channel/{channel_id} |  |
| [**serverServerIdChannelChannelIdPut**](DefaultApi.md#serverServerIdChannelChannelIdPut) | **PUT** /server/{server_id}/channel/{channel_id} |  |
| [**serverServerIdChannelCreatePost**](DefaultApi.md#serverServerIdChannelCreatePost) | **POST** /server/{server_id}/channel/create |  |
| [**serverServerIdChannelsGet**](DefaultApi.md#serverServerIdChannelsGet) | **GET** /server/{server_id}/channels |  |
| [**serverServerIdDelete**](DefaultApi.md#serverServerIdDelete) | **DELETE** /server/{server_id} |  |
| [**serverServerIdGet**](DefaultApi.md#serverServerIdGet) | **GET** /server/{server_id} |  |
| [**serverServerIdGroupCreatePost**](DefaultApi.md#serverServerIdGroupCreatePost) | **POST** /server/{server_id}/group/create |  |
| [**serverServerIdGroupGroupIdDelete**](DefaultApi.md#serverServerIdGroupGroupIdDelete) | **DELETE** /server/{server_id}/group/{group_id} |  |
| [**serverServerIdGroupGroupIdGet**](DefaultApi.md#serverServerIdGroupGroupIdGet) | **GET** /server/{server_id}/group/{group_id} |  |
| [**serverServerIdGroupGroupIdPut**](DefaultApi.md#serverServerIdGroupGroupIdPut) | **PUT** /server/{server_id}/group/{group_id} |  |
| [**serverServerIdGroupsGet**](DefaultApi.md#serverServerIdGroupsGet) | **GET** /server/{server_id}/groups |  |
| [**serverServerIdPut**](DefaultApi.md#serverServerIdPut) | **PUT** /server/{server_id} |  |
| [**serverServerIdUserUserIdBanPost**](DefaultApi.md#serverServerIdUserUserIdBanPost) | **POST** /server/{server_id}/user/{user_id}/ban |  |
| [**serverServerIdUserUserIdBansGet**](DefaultApi.md#serverServerIdUserUserIdBansGet) | **GET** /server/{server_id}/user/{user_id}/bans |  |
| [**serverServerIdUserUserIdGet**](DefaultApi.md#serverServerIdUserUserIdGet) | **GET** /server/{server_id}/user/{user_id} |  |
| [**serverServerIdUserUserIdKickPost**](DefaultApi.md#serverServerIdUserUserIdKickPost) | **POST** /server/{server_id}/user/{user_id}/kick |  |
| [**serverServerIdUserUserIdMovePost**](DefaultApi.md#serverServerIdUserUserIdMovePost) | **POST** /server/{server_id}/user/{user_id}/move |  |
| [**serverServerIdUserUserIdMutePost**](DefaultApi.md#serverServerIdUserUserIdMutePost) | **POST** /server/{server_id}/user/{user_id}/mute |  |
| [**serverServerIdUserUserIdUnmutePost**](DefaultApi.md#serverServerIdUserUserIdUnmutePost) | **POST** /server/{server_id}/user/{user_id}/unmute |  |
| [**serverServerIdUsersGet**](DefaultApi.md#serverServerIdUsersGet) | **GET** /server/{server_id}/users |  |
| [**serversGet**](DefaultApi.md#serversGet) | **GET** /servers | Get list of servers |


<a name="serverCreatePost"></a>
# **serverCreatePost**
> Server serverCreatePost(\_server\_create\_post\_request)

Create a new server

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **\_server\_create\_post\_request** | [**_server_create_post_request**](../Models/_server_create_post_request.md)|  | |

### Return type

[**Server**](../Models/Server.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdChannelChannelIdDelete"></a>
# **serverServerIdChannelChannelIdDelete**
> serverServerIdChannelChannelIdDelete(server\_id, channel\_id)



    Delete a channel

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **channel\_id** | **Integer**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdChannelChannelIdGet"></a>
# **serverServerIdChannelChannelIdGet**
> Channel serverServerIdChannelChannelIdGet(server\_id, channel\_id)



    Get channel info

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **channel\_id** | **Integer**|  | [default to null] |

### Return type

[**Channel**](../Models/Channel.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdChannelChannelIdPut"></a>
# **serverServerIdChannelChannelIdPut**
> Channel serverServerIdChannelChannelIdPut(server\_id, channel\_id, \_server\_\_server\_id\_\_channel\_\_channel\_id\_\_put\_request)



    Modify channel parameters

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **channel\_id** | **Integer**|  | [default to null] |
| **\_server\_\_server\_id\_\_channel\_\_channel\_id\_\_put\_request** | [**_server__server_id__channel__channel_id__put_request**](../Models/_server__server_id__channel__channel_id__put_request.md)|  | [optional] |

### Return type

[**Channel**](../Models/Channel.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdChannelCreatePost"></a>
# **serverServerIdChannelCreatePost**
> Channel serverServerIdChannelCreatePost(server\_id, \_server\_\_server\_id\_\_channel\_create\_post\_request)



    Create a new channel

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **\_server\_\_server\_id\_\_channel\_create\_post\_request** | [**_server__server_id__channel_create_post_request**](../Models/_server__server_id__channel_create_post_request.md)|  | |

### Return type

[**Channel**](../Models/Channel.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdChannelsGet"></a>
# **serverServerIdChannelsGet**
> List serverServerIdChannelsGet(server\_id)



    Get list of channels

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |

### Return type

[**List**](../Models/Channel.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdDelete"></a>
# **serverServerIdDelete**
> serverServerIdDelete(server\_id)



    Delete a server

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdGet"></a>
# **serverServerIdGet**
> Server serverServerIdGet(server\_id)



    Get server info

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |

### Return type

[**Server**](../Models/Server.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdGroupCreatePost"></a>
# **serverServerIdGroupCreatePost**
> Group serverServerIdGroupCreatePost(server\_id, \_server\_\_server\_id\_\_group\_create\_post\_request)



    Create a new group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **\_server\_\_server\_id\_\_group\_create\_post\_request** | [**_server__server_id__group_create_post_request**](../Models/_server__server_id__group_create_post_request.md)|  | |

### Return type

[**Group**](../Models/Group.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdGroupGroupIdDelete"></a>
# **serverServerIdGroupGroupIdDelete**
> serverServerIdGroupGroupIdDelete(server\_id, group\_id)



    Delete a group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **group\_id** | **UUID**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdGroupGroupIdGet"></a>
# **serverServerIdGroupGroupIdGet**
> Group serverServerIdGroupGroupIdGet(server\_id, group\_id)



    Get group info

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **group\_id** | **UUID**|  | [default to null] |

### Return type

[**Group**](../Models/Group.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdGroupGroupIdPut"></a>
# **serverServerIdGroupGroupIdPut**
> Group serverServerIdGroupGroupIdPut(server\_id, group\_id, \_server\_\_server\_id\_\_group\_\_group\_id\_\_put\_request)



    Modify group parameters

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **group\_id** | **UUID**|  | [default to null] |
| **\_server\_\_server\_id\_\_group\_\_group\_id\_\_put\_request** | [**_server__server_id__group__group_id__put_request**](../Models/_server__server_id__group__group_id__put_request.md)|  | [optional] |

### Return type

[**Group**](../Models/Group.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdGroupsGet"></a>
# **serverServerIdGroupsGet**
> List serverServerIdGroupsGet(server\_id)



    Get list of groups

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |

### Return type

[**List**](../Models/Group.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdPut"></a>
# **serverServerIdPut**
> Server serverServerIdPut(server\_id, \_server\_\_server\_id\_\_put\_request)



    Modify server parameters

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **\_server\_\_server\_id\_\_put\_request** | [**_server__server_id__put_request**](../Models/_server__server_id__put_request.md)|  | [optional] |

### Return type

[**Server**](../Models/Server.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdUserUserIdBanPost"></a>
# **serverServerIdUserUserIdBanPost**
> serverServerIdUserUserIdBanPost(server\_id, user\_id, \_server\_\_server\_id\_\_user\_\_user\_id\_\_ban\_post\_request)



    Ban a user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |
| **\_server\_\_server\_id\_\_user\_\_user\_id\_\_ban\_post\_request** | [**_server__server_id__user__user_id__ban_post_request**](../Models/_server__server_id__user__user_id__ban_post_request.md)|  | |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdUserUserIdBansGet"></a>
# **serverServerIdUserUserIdBansGet**
> List serverServerIdUserUserIdBansGet(server\_id)



    Get list of banned users

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |

### Return type

[**List**](../Models/ban.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdUserUserIdGet"></a>
# **serverServerIdUserUserIdGet**
> User serverServerIdUserUserIdGet(server\_id, user\_id)



    Get user info

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |

### Return type

[**User**](../Models/User.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdUserUserIdKickPost"></a>
# **serverServerIdUserUserIdKickPost**
> serverServerIdUserUserIdKickPost(server\_id, user\_id, \_server\_\_server\_id\_\_user\_\_user\_id\_\_kick\_post\_request)



    Kick a user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |
| **\_server\_\_server\_id\_\_user\_\_user\_id\_\_kick\_post\_request** | [**_server__server_id__user__user_id__kick_post_request**](../Models/_server__server_id__user__user_id__kick_post_request.md)|  | |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdUserUserIdMovePost"></a>
# **serverServerIdUserUserIdMovePost**
> serverServerIdUserUserIdMovePost(server\_id, user\_id, \_server\_\_server\_id\_\_user\_\_user\_id\_\_move\_post\_request)



    Move a user to another channel

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |
| **\_server\_\_server\_id\_\_user\_\_user\_id\_\_move\_post\_request** | [**_server__server_id__user__user_id__move_post_request**](../Models/_server__server_id__user__user_id__move_post_request.md)|  | |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="serverServerIdUserUserIdMutePost"></a>
# **serverServerIdUserUserIdMutePost**
> serverServerIdUserUserIdMutePost(server\_id, user\_id)



    Mute a user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdUserUserIdUnmutePost"></a>
# **serverServerIdUserUserIdUnmutePost**
> serverServerIdUserUserIdUnmutePost(server\_id, user\_id)



    Unmute a user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdUsersGet"></a>
# **serverServerIdUsersGet**
> _server__server_id__users_get_200_response serverServerIdUsersGet(server\_id)



    Get list of connected users

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **UUID**|  | [default to null] |

### Return type

[**_server__server_id__users_get_200_response**](../Models/_server__server_id__users_get_200_response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serversGet"></a>
# **serversGet**
> _servers_get_200_response serversGet()

Get list of servers

### Parameters
This endpoint does not need any parameter.

### Return type

[**_servers_get_200_response**](../Models/_servers_get_200_response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

