# DefaultApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**serverServerIdDelete**](DefaultApi.md#serverServerIdDelete) | **DELETE** /server/{server_id} |  |
| [**serverServerIdGet**](DefaultApi.md#serverServerIdGet) | **GET** /server/{server_id} |  |
| [**serverServerIdUserUserIdGet**](DefaultApi.md#serverServerIdUserUserIdGet) | **GET** /server/{server_id}/user/{user_id} |  |
| [**serverServerIdUserUserIdMutePost**](DefaultApi.md#serverServerIdUserUserIdMutePost) | **POST** /server/{server_id}/user/{user_id}/mute |  |
| [**serverServerIdUserUserIdUnmutePost**](DefaultApi.md#serverServerIdUserUserIdUnmutePost) | **POST** /server/{server_id}/user/{user_id}/unmute |  |
| [**serverServerIdUsersGet**](DefaultApi.md#serverServerIdUsersGet) | **GET** /server/{server_id}/users |  |
| [**serversCreatePost**](DefaultApi.md#serversCreatePost) | **POST** /servers/create | Create a new server |
| [**serversGet**](DefaultApi.md#serversGet) | **GET** /servers | Get list of servers |


<a name="serverServerIdDelete"></a>
# **serverServerIdDelete**
> serverServerIdDelete(server\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **String**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdGet"></a>
# **serverServerIdGet**
> ServerInfo serverServerIdGet(server\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **String**|  | [default to null] |

### Return type

[**ServerInfo**](../Models/ServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdUserUserIdGet"></a>
# **serverServerIdUserUserIdGet**
> UserInfo serverServerIdUserUserIdGet(server\_id, user\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **String**|  | [default to null] |
| **user\_id** | **Integer**|  | [default to null] |

### Return type

[**UserInfo**](../Models/UserInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serverServerIdUserUserIdMutePost"></a>
# **serverServerIdUserUserIdMutePost**
> serverServerIdUserUserIdMutePost(server\_id, user\_id)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **String**|  | [default to null] |
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



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **String**|  | [default to null] |
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



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **server\_id** | **String**|  | [default to null] |

### Return type

[**_server__server_id__users_get_200_response**](../Models/_server__server_id__users_get_200_response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="serversCreatePost"></a>
# **serversCreatePost**
> ServerInfo serversCreatePost(\_servers\_create\_post\_request)

Create a new server

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **\_servers\_create\_post\_request** | [**_servers_create_post_request**](../Models/_servers_create_post_request.md)|  | |

### Return type

[**ServerInfo**](../Models/ServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
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

