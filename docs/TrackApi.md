# \TrackApi

All URIs are relative to *https://sync.api.p7m.de/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_tracks**](TrackApi.md#get_tracks) | **GET** /tracks | Get all trackings of changes that happened since a given date
[**post_tracks**](TrackApi.md#post_tracks) | **POST** /tracks | Create a new tracking record



## get_tracks

> models::ListWrapperTrack get_tracks(since)
Get all trackings of changes that happened since a given date

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**since** | **String** | Only return trackings that happened since this date | [required] |

### Return type

[**models::ListWrapperTrack**](ListWrapper_Track.md)

### Authorization

[oauth](../README.md#oauth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## post_tracks

> models::Track post_tracks(new_track)
Create a new tracking record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**new_track** | [**NewTrack**](NewTrack.md) | The track record to create | [required] |

### Return type

[**models::Track**](Track.md)

### Authorization

[oauth](../README.md#oauth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

