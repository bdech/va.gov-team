# Retrieve Banner Message

## Request

**Method**: GET

**Path**: /alerts

**Parameters**:
None

**Headers**:

**optional:** these headers will only be included for users that are logged in

| Name | Type | Description |
|---|---|---|
|Authorization|JWT?|Token for access to the CRM API|
|secid|string|User security identifier|

## Response

<table>
<tr>
<td> Status </td> <td> Response </td>
</tr>
<tr>
<td> 200 </td>
<td>

```json
{ 
    "status": { 
        "code": 200, 
        "message": "OK", 
        "data": ["Issue 1 that is Impacting Submitters", "Issue 2 that is Impacting Submitters"] 
    }
}
```

</td>
</tr>
</table>

## Notes

* CC: This endpoint is necessary to retrieve any known issues on the portal that impact submitters or if we have planned maintenance an SA in CRM is able to create messages that display on the portal
