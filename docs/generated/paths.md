# My Apps API Title
My Apps API Description
Version: 1.0

## Create a quota.
```
PUT /quotas
```

### Description

Create a quota allows bla bla bla bla

### Parameters
|Name|Located in|Description|Required|
|----|----|----|----|
|body|body|MailStorageQuota|true|


### Responses
|Code|Description|
|----|----|
|204|null|
|404|Not Found|
|200|success|
|201|Created|
|401|Unauthorized|
|403|Forbidden|


### Consumes
* application/json

### Produces
* */*

## Get a quotas.
```
GET /quotas/{quotaId}
```

### Description

Get a quota allows bla bla bla bla

### Parameters
|Name|Located in|Description|Required|
|----|----|----|----|
|quotaId|path|quotaId|true|


### Responses
|Code|Description|
|----|----|
|404|Not Found|
|200|success|
|401|Unauthorized|
|403|Forbidden|


### Consumes
* application/json

### Produces
* */*

## Delete a quota.
```
DELETE /quotas/{quotaId}
```

### Description

Delete a quotas allows bla bla bla bla

### Parameters
|Name|Located in|Description|Required|
|----|----|----|----|
|quotaId|path|quotaId|true|


### Responses
|Code|Description|
|----|----|
|204|No Content|
|200|success|
|401|Unauthorized|
|403|Forbidden|


### Consumes
* application/json

### Produces
* */*

## Update a quota.
```
POST /quotas/{quotaId}
```

### Description

Update a quota allows bla bla bla bla

### Parameters
|Name|Located in|Description|Required|
|----|----|----|----|
|quotaId|path|quotaId|true|
|body|body|MailStorageQuota|true|


### Responses
|Code|Description|
|----|----|
|204|null|
|404|Not Found|
|200|success|
|201|Created|
|401|Unauthorized|
|403|Forbidden|


### Consumes
* application/json

### Produces
* */*

