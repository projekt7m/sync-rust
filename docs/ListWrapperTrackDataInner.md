# ListWrapperTrackDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**track_id** | [**uuid::Uuid**](uuid::Uuid.md) | Identification of this track record | 
**tenant_id** | [**uuid::Uuid**](uuid::Uuid.md) | The tenant this tracking belongs to | 
**object_type** | **String** | The type of object that got changes (base URL without ID) | 
**object_id** | [**uuid::Uuid**](uuid::Uuid.md) | The ID of the object that got changes | 
**modification_type** | [**models::ModificationType**](ModificationType.md) | The type of modification that had been made to the object | 
**actor_id** | [**uuid::Uuid**](uuid::Uuid.md) | The ID of the actor that performed the modification | 
**last_change** | **String** | The time when the modification happened | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


