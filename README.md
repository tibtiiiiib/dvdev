# Request

### **POST** - /2.0/index.php/request/getRequestFormAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/getRequestFormAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```

### **POST** - /2.0/index.php/request/makeRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/makeRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "requestArray[adresse_ordo]"="rue d\'ornano" \
    --data-raw "requestArray[poids_ordo]"="77" \
    --data-raw "requestArray[infimiere_tbl]"="true" \
    --data-raw "requestArray[heure_sortie]"="19:00" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "requestArray[id_patient]"="450" \
    --data-raw "requestArray[datn_ordo]"="19000101" \
    --data-raw "requestArray[tel_ordo]"="0101010201" \
    --data-raw "requestArray[tel_ordo2]"="010201020101" \
    --data-raw "requestArray[prenom_ordo]"="carolina" \
    --data-raw "requestArray[date_sortie]"="201612211828" \
    --data-raw "requestArray[comment]"="aucun" \
    --data-raw "requestArray[groupe_infimiere_tbl14]"="true" \
    --data-raw "id_user"="87" \
    --data-raw "requestArray[nom_ordo]"="deffes" \
    --data-raw "dv_sessionID"="none" \
    --data-raw "requestArray[id_infimiere_tblchoix_1_14]"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **requestArray[adresse_ordo]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "rue d\\'ornano"
  ],
  "default": "rue d\\'ornano"
}
```
- **requestArray[poids_ordo]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "77"
  ],
  "default": "77"
}
```
- **requestArray[infimiere_tbl]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "true"
  ],
  "default": "true"
}
```
- **requestArray[heure_sortie]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "19:00"
  ],
  "default": "19:00"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **requestArray[id_patient]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "450"
  ],
  "default": "450"
}
```
- **requestArray[datn_ordo]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "19000101"
  ],
  "default": "19000101"
}
```
- **requestArray[tel_ordo]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0101010201"
  ],
  "default": "0101010201"
}
```
- **requestArray[tel_ordo2]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "010201020101"
  ],
  "default": "010201020101"
}
```
- **requestArray[prenom_ordo]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "carolina"
  ],
  "default": "carolina"
}
```
- **requestArray[date_sortie]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "201612211828"
  ],
  "default": "201612211828"
}
```
- **requestArray[comment]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "aucun"
  ],
  "default": "aucun"
}
```
- **requestArray[groupe_infimiere_tbl14]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "true"
  ],
  "default": "true"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **requestArray[nom_ordo]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "deffes"
  ],
  "default": "deffes"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```
- **requestArray[id_infimiere_tblchoix_1_14]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/request/getRequestDocumentTypesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/getRequestDocumentTypesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/registerPatientForRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/registerPatientForRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_ordo"="2000" \
    --data-raw "id_patient"="2500"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_ordo** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2000"
  ],
  "default": "2000"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2500"
  ],
  "default": "2500"
}
```

### **POST** - /2.0/index.php/request/addDocumentToRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/addDocumentToRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_document"="1" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_ordo"="1" \
    --data-raw "id_requestDocumentType"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_ordo** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_requestDocumentType** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/request/getSentRequestsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/getSentRequestsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```

### **POST** - /2.0/index.php/request/getReceivedRequestsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/getReceivedRequestsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```

### **POST** - /2.0/index.php/request/cancelRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/cancelRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none" \
    --data-raw "id_ordo"="95"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```
- **id_ordo** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "95"
  ],
  "default": "95"
}
```

### **POST** - /2.0/index.php/request/acceptRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/acceptRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none" \
    --data-raw "id_ordo"="1051"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```
- **id_ordo** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1051"
  ],
  "default": "1051"
}
```

### **POST** - /2.0/index.php/request/getRequestDetailAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/getRequestDetailAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none" \
    --data-raw "id_ordo"="165"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```
- **id_ordo** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "165"
  ],
  "default": "165"
}
```

### **POST** - /2.0/index.php/request/refuseRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/refuseRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none" \
    --data-raw "id_ordo"="925"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```
- **id_ordo** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "925"
  ],
  "default": "925"
}
```

### **POST** - /2.0/index.php/request/deleteFavoriteRequestAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/request/deleteFavoriteRequestAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "favoriteName"="favori 2" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dv_sessionID"="none"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **favoriteName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "favori 2"
  ],
  "default": "favori 2"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dv_sessionID** should respect the following schema:

```
{
  "type": "string",
  "default": "none"
}
```

### **POST** - /2.0/index.php/document/getDocumentsForPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/document/getDocumentsForPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "offset"="0" \
    --data-raw "id_patient"="133"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **offset** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0"
  ],
  "default": "0"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "133"
  ],
  "default": "133"
}
```

### **POST** - /2.0/index.php/document/getDocumentInformationsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/document/getDocumentInformationsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_document"="3"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "3"
  ],
  "default": "3"
}
```

### **POST** - /2.0/index.php/document/uploadDocumentAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/document/uploadDocumentAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "title"="Titre Doc" \
    --data-raw "file"="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" \
    --data-raw "fk_idPatient"="33"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **title** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Titre Doc"
  ],
  "default": "Titre Doc"
}
```
- **file** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "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"
  ],
  "default": "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"
}
```
- **fk_idPatient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "33"
  ],
  "default": "33"
}
```

### **POST** - /2.0/index.php/document/refreshExternalDocumentListAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/document/refreshExternalDocumentListAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "fk_idPatient"="1279" \
    --data-raw "offset"="0"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **fk_idPatient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1279"
  ],
  "default": "1279"
}
```
- **offset** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0"
  ],
  "default": "0"
}
```

### **POST** - /2.0/index.php/document/loadExternalDocumentAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/document/loadExternalDocumentAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_document"="583"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "583"
  ],
  "default": "583"
}
```

### **POST** - /2.0/index.php/patientadministrative/getUserPatientsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getUserPatientsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **GET** - /2.0/index.php/patientadministrative/getUserPatientsAction/

#### CURL

```sh
curl -X GET "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getUserPatientsAction/\
?id_user=87&sessionID=8758873590b28669.99489364" \
    -H "Content-Type: application/x-www-form-urlencoded"
```

#### Query Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

### **POST** - /2.0/index.php/patientadministrative/getUserPatientsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getUserPatientsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientadministrative/getAllPatientInformationsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getAllPatientInformationsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="388"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "388"
  ],
  "default": "388"
}
```

### **POST** - /2.0/index.php/patientadministrative/createPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/createPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "fnames"="Paul Germain" \
    --data-raw "mutual"="Mutuelle De L'Ouest" \
    --data-raw "socialSecurityNumber"="123123789456126" \
    --data-raw "height"="167" \
    --data-raw "lastname"="Delerue" \
    --data-raw "firstname"="Alfred" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "birthdate"="19500112" \
    --data-raw "genre"="2" \
    --data-raw "mname"="$mname" \
    --data-raw "id_user"="87"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **fnames** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Paul Germain"
  ],
  "default": "Paul Germain"
}
```
- **mutual** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Mutuelle De L'Ouest"
  ],
  "default": "Mutuelle De L'Ouest"
}
```
- **socialSecurityNumber** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "123123789456126"
  ],
  "default": "123123789456126"
}
```
- **height** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "167"
  ],
  "default": "167"
}
```
- **lastname** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Delerue"
  ],
  "default": "Delerue"
}
```
- **firstname** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Alfred"
  ],
  "default": "Alfred"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **birthdate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "19500112"
  ],
  "default": "19500112"
}
```
- **genre** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **mname** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    ""
  ]
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```

### **POST** - /2.0/index.php/patientadministrative/editPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/editPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "fnames"="Henriette, Paule" \
    --data-raw "mutual"="Malakoff" \
    --data-raw "socialSecurityNumber"="123789456" \
    --data-raw "lastname"="Pouliche" \
    --data-raw "firstname"="Mauricette" \
    --data-raw "id_patient"="388" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "birthdate"="19400520" \
    --data-raw "genre"="2" \
    --data-raw "mname"="Delerue" \
    --data-raw "id_user"="87"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **fnames** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Henriette, Paule"
  ],
  "default": "Henriette, Paule"
}
```
- **mutual** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Malakoff"
  ],
  "default": "Malakoff"
}
```
- **socialSecurityNumber** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "123789456"
  ],
  "default": "123789456"
}
```
- **lastname** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Pouliche"
  ],
  "default": "Pouliche"
}
```
- **firstname** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Mauricette"
  ],
  "default": "Mauricette"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "388"
  ],
  "default": "388"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **birthdate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "19400520"
  ],
  "default": "19400520"
}
```
- **genre** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **mname** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Delerue"
  ],
  "default": "Delerue"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```

### **POST** - /2.0/index.php/patientadministrative/createContactForPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/createContactForPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "email"="email" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="8"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **email** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "email"
  ],
  "default": "email"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```

### **POST** - /2.0/index.php/patientadministrative/getEmergencyContactTypesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getEmergencyContactTypesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientadministrative/createEmergencyContactForPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/createEmergencyContactForPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "phone"="0203010201" \
    --data-raw "role"="Médecin Généraliste" \
    --data-raw "id_patient"="388" \
    --data-raw "email"="email" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "rank"="2" \
    --data-raw "name"="Gabriel Lacoste" \
    --data-raw "id_user"="87"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **phone** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0203010201"
  ],
  "default": "0203010201"
}
```
- **role** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Médecin Généraliste"
  ],
  "default": "Médecin Généraliste"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "388"
  ],
  "default": "388"
}
```
- **email** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "email"
  ],
  "default": "email"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **rank** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **name** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Gabriel Lacoste"
  ],
  "default": "Gabriel Lacoste"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```

### **POST** - /2.0/index.php/patientadministrative/deletePatientEmergencyContactAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/deletePatientEmergencyContactAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_emergencyContact"="13"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_emergencyContact** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "13"
  ],
  "default": "13"
}
```

### **POST** - /2.0/index.php/patientadministrative/createAddressForPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/createAddressForPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "street"="14 Boulevard Pasteur" \
    --data-raw "city"="Paris" \
    --data-raw "isMainAddress"="1" \
    --data-raw "country"="France" \
    --data-raw "complement"="Cour Droite" \
    --data-raw "id_patient"="8" \
    --data-raw "postcode"="75001" \
    --data-raw "googlePlaceID"="12" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_user"="87"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **street** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "14 Boulevard Pasteur"
  ],
  "default": "14 Boulevard Pasteur"
}
```
- **city** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Paris"
  ],
  "default": "Paris"
}
```
- **isMainAddress** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **country** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "France"
  ],
  "default": "France"
}
```
- **complement** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Cour Droite"
  ],
  "default": "Cour Droite"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```
- **postcode** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "75001"
  ],
  "default": "75001"
}
```
- **googlePlaceID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12"
  ],
  "default": "12"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```

### **POST** - /2.0/index.php/patientadministrative/editPatientAddressAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/editPatientAddressAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "street"="14 Boulevard Pasteur" \
    --data-raw "city"="Paris" \
    --data-raw "isMainAddress"="1" \
    --data-raw "country"="France" \
    --data-raw "complement"="Cour Droite" \
    --data-raw "id_patient"="8" \
    --data-raw "postcode"="75001" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_user"="87"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **street** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "14 Boulevard Pasteur"
  ],
  "default": "14 Boulevard Pasteur"
}
```
- **city** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Paris"
  ],
  "default": "Paris"
}
```
- **isMainAddress** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **country** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "France"
  ],
  "default": "France"
}
```
- **complement** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Cour Droite"
  ],
  "default": "Cour Droite"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```
- **postcode** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "75001"
  ],
  "default": "75001"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```

### **POST** - /2.0/index.php/patientadministrative/getUserPatientsWithSearchStringAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getUserPatientsWithSearchStringAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientadministrative/getOwnLinkSheetAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientadministrative/getOwnLinkSheetAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_userPatient"="2" \
    --data-raw "sessionID"="258860ee182d642.95360284"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_userPatient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "258860ee182d642.95360284"
  ],
  "default": "258860ee182d642.95360284"
}
```

### **POST** - /2.0/index.php/patientantecedent/getAntecedentsForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientantecedent/getAntecedentsForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "offset"="0" \
    --data-raw "id_patient"="133"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **offset** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0"
  ],
  "default": "0"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "133"
  ],
  "default": "133"
}
```

### **POST** - /2.0/index.php/patientantecedent/createAntecedentForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientantecedent/createAntecedentForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "content"="Yayaya I'm lorde" \
    --data-raw "id_document"="1" \
    --data-raw "id_patient"="33"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **content** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Yayaya I'm lorde"
  ],
  "default": "Yayaya I'm lorde"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "33"
  ],
  "default": "33"
}
```

### **POST** - /2.0/index.php/patientantecedent/deleteAntecedentAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientantecedent/deleteAntecedentAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_antecedent"="7"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_antecedent** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "7"
  ],
  "default": "7"
}
```

### **POST** - /2.0/index.php/patientcaremotive/getCareMotivesForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientcaremotive/getCareMotivesForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="33"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "33"
  ],
  "default": "33"
}
```

### **POST** - /2.0/index.php/patientcaremotive/editCareMotiveForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientcaremotive/editCareMotiveForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "content"="Yayaya I'm lorde" \
    --data-raw "id_careMotive"="114"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **content** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Yayaya I'm lorde"
  ],
  "default": "Yayaya I'm lorde"
}
```
- **id_careMotive** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "114"
  ],
  "default": "114"
}
```

### **POST** - /2.0/index.php/patientcaremotive/deleteCareMotiveForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientcaremotive/deleteCareMotiveForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_careMotive"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_careMotive** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/patientconstant/getLastConstantsForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientconstant/getLastConstantsForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="37"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "37"
  ],
  "default": "37"
}
```

### **POST** - /2.0/index.php/patientconstant/setConstantForFolderAction/

#### Description
  

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientconstant/setConstantForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_patient"="37" \
    --data-raw "temperature"="37.77" \
    --data-raw "stools"="1" \
    --data-raw "bloodPressureLow"="10" \
    --data-raw "bloodSugar"="12" \
    --data-raw "diuresis"="1000" \
    --data-raw "weight"="254.234" \
    --data-raw "id_user"="87" \
    --data-raw "pulse"="70" \
    --data-raw "bloodPressureHigh"="15" \
    --data-raw "saturation"="98" \
    --data-raw "breathingRate"="130" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "37"
  ],
  "default": "37"
}
```
- **temperature** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "37.77"
  ],
  "default": "37.77"
}
```
- **stools** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **bloodPressureLow** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "10"
  ],
  "default": "10"
}
```
- **bloodSugar** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12"
  ],
  "default": "12"
}
```
- **diuresis** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1000"
  ],
  "default": "1000"
}
```
- **weight** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "254.234"
  ],
  "default": "254.234"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **pulse** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "70"
  ],
  "default": "70"
}
```
- **bloodPressureHigh** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "15"
  ],
  "default": "15"
}
```
- **saturation** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "98"
  ],
  "default": "98"
}
```
- **breathingRate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "130"
  ],
  "default": "130"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientconstant/getConstantsByCategoryAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientconstant/getConstantsByCategoryAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "bloodPressure"="1" \
    --data-raw "offset"="5" \
    --data-raw "id_patient"="37"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **bloodPressure** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **offset** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "5"
  ],
  "default": "5"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "37"
  ],
  "default": "37"
}
```

### **POST** - /2.0/index.php/patientconstant/deleteConstantAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientconstant/deleteConstantAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_constantBloodPressure"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_constantBloodPressure** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/patientdiary/getDiaryElementsForPatientAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientdiary/getDiaryElementsForPatientAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="115"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "115"
  ],
  "default": "115"
}
```

### **POST** - /2.0/index.php/patientevaluation/getEvaluationCriteriasAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientevaluation/getEvaluationCriteriasAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientevaluation/getEvaluationSessionsForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientevaluation/getEvaluationSessionsForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="276"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "276"
  ],
  "default": "276"
}
```

### **POST** - /2.0/index.php/patientevaluation/createEvaluationSessionForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientevaluation/createEvaluationSessionForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/patientevaluation/setCriteriaInEvaluationSessionAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientevaluation/setCriteriaInEvaluationSessionAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_evaluationDependance"="1" \
    --data-raw "level"="1" \
    --data-raw "id_evaluationSession"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_evaluationDependance** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **level** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_evaluationSession** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/patientfolder/getFolderContentAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientfolder/getFolderContentAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="276"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "276"
  ],
  "default": "276"
}
```

### **POST** - /2.0/index.php/patientnetwork/getPatientNetworkAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/getPatientNetworkAction/" \
    -H "Content-Type: application/x-www-form-urlencoded; charset=utf-8" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded; charset=utf-8"
  ],
  "default": "application/x-www-form-urlencoded; charset=utf-8"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientnetwork/getFolderNetworkAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/getFolderNetworkAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="4"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "4"
  ],
  "default": "4"
}
```

### **POST** - /2.0/index.php/patientnetwork/setUserAsFolderAdministratorAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/setUserAsFolderAdministratorAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="306" \
    --data-raw "id_userFolderAdministrator"="91"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "306"
  ],
  "default": "306"
}
```
- **id_userFolderAdministrator** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "91"
  ],
  "default": "91"
}
```

### **POST** - /2.0/index.php/patientnetwork/addUserToFolderNetworkAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/addUserToFolderNetworkAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="1" \
    --data-raw "id_userToAdd"="36"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_userToAdd** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "36"
  ],
  "default": "36"
}
```

### **POST** - /2.0/index.php/patientnetwork/removeUserFromFolderNetworkAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/removeUserFromFolderNetworkAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="18" \
    --data-raw "id_userFolderAdministrator"="36"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "18"
  ],
  "default": "18"
}
```
- **id_userFolderAdministrator** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "36"
  ],
  "default": "36"
}
```

### **POST** - /2.0/index.php/patientnetwork/createNurseFolderForPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/createNurseFolderForPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="388"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "388"
  ],
  "default": "388"
}
```

### **POST** - /2.0/index.php/patientnetwork/getArchiveFolderMotivesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/getArchiveFolderMotivesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientnetwork/closeNurseFolderNetworkAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnetwork/closeNurseFolderNetworkAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="259" \
    --data-raw "id_folderArchiveMotive"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "259"
  ],
  "default": "259"
}
```
- **id_folderArchiveMotive** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/patientnursingcare/getActsForDateAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnursingcare/getActsForDateAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_patient"="93" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "date"="20160519"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "93"
  ],
  "default": "93"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **date** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20160519"
  ],
  "default": "20160519"
}
```

### **POST** - /2.0/index.php/patientnursingcare/getNursingCareActsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnursingcare/getNursingCareActsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientnursingcare/createActAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnursingcare/createActAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_patient"="132" \
    --data-raw "description"="Séance de test" \
    --data-raw "days[1]"="3" \
    --data-raw "startingDate"="20160314" \
    --data-raw "endingDate"="20160325" \
    --data-raw "slots[1]"="4" \
    --data-raw "id_nursingCareActSub"="2,3,4" \
    --data-raw "days[2]"="4" \
    --data-raw "id_nursingCareActMain"="1" \
    --data-raw "id_user"="87" \
    --data-raw "days[0]"="1" \
    --data-raw "slots[0]"="2" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "132"
  ],
  "default": "132"
}
```
- **description** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Séance de test"
  ],
  "default": "Séance de test"
}
```
- **days[1]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "3"
  ],
  "default": "3"
}
```
- **startingDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20160314"
  ],
  "default": "20160314"
}
```
- **endingDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20160325"
  ],
  "default": "20160325"
}
```
- **slots[1]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "4"
  ],
  "default": "4"
}
```
- **id_nursingCareActSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2,3,4"
  ],
  "default": "2,3,4"
}
```
- **days[2]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "4"
  ],
  "default": "4"
}
```
- **id_nursingCareActMain** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **days[0]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **slots[0]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/patientnursingcare/createActForMultipleDatesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnursingcare/createActForMultipleDatesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "description"="description" \
    --data-raw "id_user"="87" \
    --data-raw "endingDate"="20161220" \
    --data-raw "dates[1]"="20161220,2" \
    --data-raw "id_nursingCareActMain"="1" \
    --data-raw "startingDate"="20161120" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "dates[0]"="20161120,1" \
    --data-raw "id_nursingCareActSub"="2" \
    --data-raw "id_folder"="251"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **description** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "description"
  ],
  "default": "description"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **endingDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161220"
  ],
  "default": "20161220"
}
```
- **dates[1]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161220,2"
  ],
  "default": "20161220,2"
}
```
- **id_nursingCareActMain** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **startingDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161120"
  ],
  "default": "20161120"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **dates[0]** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161120,1"
  ],
  "default": "20161120,1"
}
```
- **id_nursingCareActSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "251"
  ],
  "default": "251"
}
```

### **POST** - /2.0/index.php/patientnursingcare/createUniqueActAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnursingcare/createUniqueActAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "date"="20160727" \
    --data-raw "slot"="2" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "description"="Séance unique" \
    --data-raw "id_nursingCareActMain"="1" \
    --data-raw "id_nursingCareActSub"="2" \
    --data-raw "id_folder"="18"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **date** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20160727"
  ],
  "default": "20160727"
}
```
- **slot** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **description** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Séance unique"
  ],
  "default": "Séance unique"
}
```
- **id_nursingCareActMain** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_nursingCareActSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "18"
  ],
  "default": "18"
}
```

### **POST** - /2.0/index.php/patientnursingcare/changeActStatusAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patientnursingcare/changeActStatusAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_nursingCareProgram"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_nursingCareProgram** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/patienttransmission/getSubTargetsForMainTargetAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/getSubTargetsForMainTargetAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="4"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "4"
  ],
  "default": "4"
}
```

### **POST** - /2.0/index.php/patienttransmission/getOpenTargetsForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/getOpenTargetsForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="8"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```

### **POST** - /2.0/index.php/patienttransmission/getTransmissionsForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/getTransmissionsForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="115"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "115"
  ],
  "default": "115"
}
```

### **POST** - /2.0/index.php/patienttransmission/createNewTransmissionSessionForPatientAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/createNewTransmissionSessionForPatientAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="8"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```

### **POST** - /2.0/index.php/patienttransmission/createNewTargetForTransmissionSessionAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/createNewTargetForTransmissionSessionAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_targetSub"="2" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_transmissionSession"="1" \
    --data-raw "id_patient"="8"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_targetSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_transmissionSession** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```

### **POST** - /2.0/index.php/patienttransmission/completeExistingTargetForTransmissionSessionAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/completeExistingTargetForTransmissionSessionAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_patient"="8" \
    --data-raw "id_targetSub"="2" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_transmissionSession"="1" \
    --data-raw "id_transmissionTarget"="6"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```
- **id_targetSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_transmissionSession** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_transmissionTarget** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "6"
  ],
  "default": "6"
}
```

### **POST** - /2.0/index.php/patienttransmission/closeTargetForTransmissionSessionAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/closeTargetForTransmissionSessionAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "id_transmissionSession"="1" \
    --data-raw "id_patient"="8" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_document"="1" \
    --data-raw "comment"="terminey" \
    --data-raw "id_targetSub"="2" \
    --data-raw "id_transmissionTarget"="6"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **id_transmissionSession** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **comment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "terminey"
  ],
  "default": "terminey"
}
```
- **id_targetSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **id_transmissionTarget** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "6"
  ],
  "default": "6"
}
```

### **POST** - /2.0/index.php/patienttransmission/getAllTransmissionsForTargetAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/getAllTransmissionsForTargetAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "id_transmissionSession"="1" \
    --data-raw "id_patient"="8" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_document"="1" \
    --data-raw "comment"="terminey" \
    --data-raw "id_targetSub"="2" \
    --data-raw "id_transmissionTarget"="6"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **id_transmissionSession** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8"
  ],
  "default": "8"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **comment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "terminey"
  ],
  "default": "terminey"
}
```
- **id_targetSub** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **id_transmissionTarget** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "6"
  ],
  "default": "6"
}
```

### **POST** - /2.0/index.php/patienttransmission/checkNewTransmissionsForServicesAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttransmission/checkNewTransmissionsForServicesAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_folder"="400" \
    --data-raw "id_targetMain"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_folder** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "400"
  ],
  "default": "400"
}
```
- **id_targetMain** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/patienttreatment/createTreatmentForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttreatment/createTreatmentForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "content"="Yayaya I'm lorde" \
    --data-raw "id_document"="1" \
    --data-raw "id_patient"="33"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **content** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Yayaya I'm lorde"
  ],
  "default": "Yayaya I'm lorde"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "33"
  ],
  "default": "33"
}
```

### **POST** - /2.0/index.php/patienttreatment/getTreatmentsForFolderAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttreatment/getTreatmentsForFolderAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_patient"="133"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_patient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "133"
  ],
  "default": "133"
}
```

### **POST** - /2.0/index.php/patienttreatment/deleteTreatmentAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/patienttreatment/deleteTreatmentAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_treatment"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_treatment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/exchange/getExchangesAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/exchange/getExchangesAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/exchange/createExchangeAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/exchange/createExchangeAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/news/getNewsAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/news/getNewsAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "sender"="Groupe 1 (Utilisateur)" \
    --data-raw "content"="TEST" \
    --data-raw "id_user"="87" \
    --data-raw "fk_idEvent"="0" \
    --data-raw "fk_idAttachment"="NULL" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "fk_idSender_group"="2" \
    --data-raw "recipient"="Service de Test 1" \
    --data-raw "type"="1" \
    --data-raw "fk_idRecipient_service"="7"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **sender** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Groupe 1 (Utilisateur)"
  ],
  "default": "Groupe 1 (Utilisateur)"
}
```
- **content** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "TEST"
  ],
  "default": "TEST"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **fk_idEvent** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0"
  ],
  "default": "0"
}
```
- **fk_idAttachment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "NULL"
  ],
  "default": "NULL"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **fk_idSender_group** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **recipient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Service de Test 1"
  ],
  "default": "Service de Test 1"
}
```
- **type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **fk_idRecipient_service** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "7"
  ],
  "default": "7"
}
```

### **POST** - /2.0/index.php/news/createNewsAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/news/createNewsAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "sender"="Groupe 1 (Utilisateur)" \
    --data-raw "content"="TEST" \
    --data-raw "id_user"="87" \
    --data-raw "fk_idEvent"="0" \
    --data-raw "fk_idAttachment"="NULL" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "fk_idSender_group"="2" \
    --data-raw "recipient"="Service de Test 1" \
    --data-raw "type"="1" \
    --data-raw "fk_idRecipient_service"="7"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **sender** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Groupe 1 (Utilisateur)"
  ],
  "default": "Groupe 1 (Utilisateur)"
}
```
- **content** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "TEST"
  ],
  "default": "TEST"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **fk_idEvent** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "0"
  ],
  "default": "0"
}
```
- **fk_idAttachment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "NULL"
  ],
  "default": "NULL"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **fk_idSender_group** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **recipient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Service de Test 1"
  ],
  "default": "Service de Test 1"
}
```
- **type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **fk_idRecipient_service** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "7"
  ],
  "default": "7"
}
```

### **POST** - /2.0/index.php/predictive/getAlertPlugsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/getAlertPlugsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="12658481b5bc33c10.60237584"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12658481b5bc33c10.60237584"
  ],
  "default": "12658481b5bc33c10.60237584"
}
```

### **POST** - /2.0/index.php/predictive/createNewAlertPlugAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/createNewAlertPlugAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "patientLastName"="Michel" \
    --data-raw "socialConsultationRequired"="1" \
    --data-raw "patientBirthName"="Michel" \
    --data-raw "fk_idService"="7" \
    --data-raw "socialCardFilled"="1" \
    --data-raw "viaTrajectoireAdmissionToComplete"="BLABLA" \
    --data-raw "nextRevisionDate"="20170101" \
    --data-raw "socialConsultationRequiredDate"="12/12/12" \
    --data-raw "id_user"="87" \
    --data-raw "viaTrajectoireRequestStatus"="1" \
    --data-raw "viaTrajectoireRequested"="1" \
    --data-raw "patientFirstName"="Jacques" \
    --data-raw "hospitalizationDate"="20161001" \
    --data-raw "socialConsultation"="1" \
    --data-raw "viaTrajectoireRequestSentDate"="14 décembre 2000" \
    --data-raw "viaTrajectoireRequestResponseDate"="26200112" \
    --data-raw "serviceEntryDate"="20161001" \
    --data-raw "patientLocalIdentifier"="1234" \
    --data-raw "patientBirthDate"="19601010" \
    --data-raw "patientFutureKnown"="1" \
    --data-raw "socialConsultationDates"="24/12 et 26/12" \
    --data-raw "pronouncedExitButRefused"="2" \
    --data-raw "viaTrajectoireRequestUnitsRequired"="14 unités 3cc de mylixine" \
    --data-raw "allStayInService"="1" \
    --data-raw "viaTrajectoireRequestDate"="12/11/12" \
    --data-raw "patientExitMode"="1" \
    --data-raw "comment"="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum" \
    --data-raw "pronouncedExitDate"="12 décembre 2015" \
    --data-raw "treatmentState"="3" \
    --data-raw "hospitalizationMotive"="Perte de mobilité triple double double floflo responsable"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **patientLastName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Michel"
  ],
  "default": "Michel"
}
```
- **socialConsultationRequired** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **patientBirthName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Michel"
  ],
  "default": "Michel"
}
```
- **fk_idService** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "7"
  ],
  "default": "7"
}
```
- **socialCardFilled** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireAdmissionToComplete** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "BLABLA"
  ],
  "default": "BLABLA"
}
```
- **nextRevisionDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20170101"
  ],
  "default": "20170101"
}
```
- **socialConsultationRequiredDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12/12/12"
  ],
  "default": "12/12/12"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **viaTrajectoireRequestStatus** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireRequested** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **patientFirstName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Jacques"
  ],
  "default": "Jacques"
}
```
- **hospitalizationDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161001"
  ],
  "default": "20161001"
}
```
- **socialConsultation** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireRequestSentDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "14 décembre 2000"
  ],
  "default": "14 décembre 2000"
}
```
- **viaTrajectoireRequestResponseDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "26200112"
  ],
  "default": "26200112"
}
```
- **serviceEntryDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161001"
  ],
  "default": "20161001"
}
```
- **patientLocalIdentifier** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1234"
  ],
  "default": "1234"
}
```
- **patientBirthDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "19601010"
  ],
  "default": "19601010"
}
```
- **patientFutureKnown** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **socialConsultationDates** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "24/12 et 26/12"
  ],
  "default": "24/12 et 26/12"
}
```
- **pronouncedExitButRefused** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **viaTrajectoireRequestUnitsRequired** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "14 unités 3cc de mylixine"
  ],
  "default": "14 unités 3cc de mylixine"
}
```
- **allStayInService** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireRequestDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12/11/12"
  ],
  "default": "12/11/12"
}
```
- **patientExitMode** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **comment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
  ],
  "default": "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
}
```
- **pronouncedExitDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12 décembre 2015"
  ],
  "default": "12 décembre 2015"
}
```
- **treatmentState** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "3"
  ],
  "default": "3"
}
```
- **hospitalizationMotive** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Perte de mobilité triple double double floflo responsable"
  ],
  "default": "Perte de mobilité triple double double floflo responsable"
}
```

### **POST** - /2.0/index.php/predictive/editAlertPlugAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/editAlertPlugAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "patientLastName"="Michel" \
    --data-raw "socialConsultationRequired"="1" \
    --data-raw "patientBirthName"="Michel" \
    --data-raw "fk_idService"="7" \
    --data-raw "socialCardFilled"="1" \
    --data-raw "viaTrajectoireAdmissionToComplete"="BLABLA" \
    --data-raw "nextRevisionDate"="20170101" \
    --data-raw "id_predictiveAlertPlug"="1" \
    --data-raw "id_user"="87" \
    --data-raw "socialConsultationRequiredDate"="12/12/12" \
    --data-raw "viaTrajectoireRequestStatus"="1" \
    --data-raw "viaTrajectoireRequested"="1" \
    --data-raw "patientFirstName"="Jacques" \
    --data-raw "hospitalizationDate"="20161001" \
    --data-raw "socialConsultation"="1" \
    --data-raw "viaTrajectoireRequestSentDate"="14 décembre 2000" \
    --data-raw "viaTrajectoireRequestResponseDate"="26200112" \
    --data-raw "serviceEntryDate"="20161001" \
    --data-raw "patientLocalIdentifier"="1234" \
    --data-raw "patientBirthDate"="19601010" \
    --data-raw "patientFutureKnown"="1" \
    --data-raw "socialConsultationDates"="24/12 et 26/12" \
    --data-raw "pronouncedExitButRefused"="2" \
    --data-raw "viaTrajectoireRequestUnitsRequired"="14 unités 3cc de mylixine" \
    --data-raw "allStayInService"="1" \
    --data-raw "viaTrajectoireRequestDate"="12/11/12" \
    --data-raw "patientExitMode"="1" \
    --data-raw "comment"="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum" \
    --data-raw "pronouncedExitDate"="12 décembre 2015" \
    --data-raw "treatmentState"="3" \
    --data-raw "hospitalizationMotive"="Perte de mobilité triple double double floflo responsable"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **patientLastName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Michel"
  ],
  "default": "Michel"
}
```
- **socialConsultationRequired** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **patientBirthName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Michel"
  ],
  "default": "Michel"
}
```
- **fk_idService** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "7"
  ],
  "default": "7"
}
```
- **socialCardFilled** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireAdmissionToComplete** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "BLABLA"
  ],
  "default": "BLABLA"
}
```
- **nextRevisionDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20170101"
  ],
  "default": "20170101"
}
```
- **id_predictiveAlertPlug** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **socialConsultationRequiredDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12/12/12"
  ],
  "default": "12/12/12"
}
```
- **viaTrajectoireRequestStatus** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireRequested** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **patientFirstName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Jacques"
  ],
  "default": "Jacques"
}
```
- **hospitalizationDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161001"
  ],
  "default": "20161001"
}
```
- **socialConsultation** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireRequestSentDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "14 décembre 2000"
  ],
  "default": "14 décembre 2000"
}
```
- **viaTrajectoireRequestResponseDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "26200112"
  ],
  "default": "26200112"
}
```
- **serviceEntryDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "20161001"
  ],
  "default": "20161001"
}
```
- **patientLocalIdentifier** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1234"
  ],
  "default": "1234"
}
```
- **patientBirthDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "19601010"
  ],
  "default": "19601010"
}
```
- **patientFutureKnown** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **socialConsultationDates** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "24/12 et 26/12"
  ],
  "default": "24/12 et 26/12"
}
```
- **pronouncedExitButRefused** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **viaTrajectoireRequestUnitsRequired** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "14 unités 3cc de mylixine"
  ],
  "default": "14 unités 3cc de mylixine"
}
```
- **allStayInService** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **viaTrajectoireRequestDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12/11/12"
  ],
  "default": "12/11/12"
}
```
- **patientExitMode** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **comment** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
  ],
  "default": "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
}
```
- **pronouncedExitDate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "12 décembre 2015"
  ],
  "default": "12 décembre 2015"
}
```
- **treatmentState** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "3"
  ],
  "default": "3"
}
```
- **hospitalizationMotive** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Perte de mobilité triple double double floflo responsable"
  ],
  "default": "Perte de mobilité triple double double floflo responsable"
}
```

### **POST** - /2.0/index.php/predictive/getServicesLandmarksAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/getServicesLandmarksAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/predictive/getMonitoredServicesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/getMonitoredServicesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/predictive/activateAlertForServiceAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/activateAlertForServiceAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_predictiveServiceLandmark"="1" \
    --data-raw "activate"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_predictiveServiceLandmark** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **activate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/predictive/setEffectiveLandmarkForServiceAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/setEffectiveLandmarkForServiceAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_predictiveServiceLandmark"="1" \
    --data-raw "activate"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_predictiveServiceLandmark** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```
- **activate** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/predictive/getRSSFilesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/getRSSFilesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/predictive/launchFileAnalysisAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/launchFileAnalysisAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_document"="450"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_document** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "450"
  ],
  "default": "450"
}
```

### **POST** - /2.0/index.php/predictive/loadNewRSSFileAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/predictive/loadNewRSSFileAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "fileTitle"="chocho'lkdzq" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "file64"="dGVzdA=="
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **fileTitle** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "chocho'lkdzq"
  ],
  "default": "chocho'lkdzq"
}
```
- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **file64** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "dGVzdA=="
  ],
  "default": "dGVzdA=="
}
```

### **POST** - /2.0/index.php/task/createTaskAction

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/task/createTaskAction" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "fk_idPatient"="271" \
    --data-raw "fk_idUser"="36"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **fk_idPatient** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "271"
  ],
  "default": "271"
}
```
- **fk_idUser** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "36"
  ],
  "default": "36"
}
```

### **POST** - /2.0/index.php/territory/connectToFunctionAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/connectToFunctionAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_function"="1"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_function** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1"
  ],
  "default": "1"
}
```

### **POST** - /2.0/index.php/territory/getUserServicesAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getUserServicesAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/territory/getUserGroupsAdminRightsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getUserGroupsAdminRightsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/territory/getAllExternalUsersAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getAllExternalUsersAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/territory/getUserGroupsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getUserGroupsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/territory/getUserServicesAdminRightsAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getUserServicesAdminRightsAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/territory/getAllUsersFromEstablishmentAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getAllUsersFromEstablishmentAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_place"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_place** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/territory/getPlaceFunctionsAllAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/territory/getPlaceFunctionsAllAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "fk_idPlace"="2"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **fk_idPlace** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```

### **POST** - /2.0/index.php/usersession/safeConnectDVUserAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usersession/safeConnectDVUserAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "login"="tlefevre" \
    --data-raw "deviceID"="1-12" \
    --data-raw "password"="passpass"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **login** should respect the following schema:

```
{
  "type": "string",
  "default": "tlefevre"
}
```
- **deviceID** should respect the following schema:

```
{
  "type": "string",
  "default": "1-12"
}
```
- **password** should respect the following schema:

```
{
  "type": "string",
  "default": "passpass"
}
```

### **POST** - /2.0/index.php/usersession/activateDeviceAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usersession/activateDeviceAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "deviceID"="1-12" \
    --data-raw "activationCode"="231331" \
    --data-raw "deviceName"="Postman"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **deviceID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "1-12"
  ],
  "default": "1-12"
}
```
- **activationCode** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "231331"
  ],
  "default": "231331"
}
```
- **deviceName** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "Postman"
  ],
  "default": "Postman"
}
```

### **POST** - /2.0/index.php/usersession/disconnectDVUserAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usersession/disconnectDVUserAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```

### **POST** - /2.0/index.php/usersession/getSmsToSendAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usersession/getSmsToSendAction/" \
    -H "Content-Type: multipart/form-data" \
    --data-raw "$body"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "multipart/form-data"
  ],
  "default": "multipart/form-data"
}
```

#### Body Parameters

- **body** should respect the following schema:

```
{
  "type": "string",
  "default": ""
}
```

### **POST** - /2.0/index.php/usersession/setSmsIsSentAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usersession/setSmsIsSentAction/" \
    -H "Content-Type: multipart/form-data" \
    --data-raw "$body"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "multipart/form-data"
  ],
  "default": "multipart/form-data"
}
```

#### Body Parameters

- **body** should respect the following schema:

```
{
  "type": "string",
  "default": "29"
}
```

### **GET** - /2.0/index.php/usersession/invalidSessionsAction/

#### CURL

```sh
curl -X GET "https://dv-api.itmnl.com/2.0/index.php/usersession/invalidSessionsAction/" \
    -H "Content-Type: text/plain"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "text/plain"
  ],
  "default": "text/plain"
}
```

### **POST** - /2.0/index.php/userpatientsession/safeConnectPatientUserAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/userpatientsession/safeConnectPatientUserAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "email"="dimts@monali.fr" \
    --data-raw "password"="5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **email** should respect the following schema:

```
{
  "type": "string",
  "default": "dimts@monali.fr"
}
```
- **password** should respect the following schema:

```
{
  "type": "string",
  "default": "5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8"
}
```

### **POST** - /2.0/index.php/userpatientsession/disconnectPatientUserAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/userpatientsession/disconnectPatientUserAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_patientUser"="2" \
    --data-raw "sessionID"="258860ee182d642.95360284"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_patientUser** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "2"
  ],
  "default": "2"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "258860ee182d642.95360284"
  ],
  "default": "258860ee182d642.95360284"
}
```

### **POST** - /2.0/index.php/usermanagement/getUsersMatchingStringAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usermanagement/getUsersMatchingStringAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "string"="emm"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **string** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "emm"
  ],
  "default": "emm"
}
```

### **POST** - /2.0/index.php/usermanagement/getUserNameAction/

#### CURL

```sh
curl -X POST "https://dv-api.itmnl.com/2.0/index.php/usermanagement/getUserNameAction/" \
    -H "Content-Type: application/x-www-form-urlencoded" \
    --data-raw "id_user"="87" \
    --data-raw "sessionID"="8758873590b28669.99489364" \
    --data-raw "id_searchedUser"="22"
```

#### Header Parameters

- **Content-Type** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "application/x-www-form-urlencoded"
  ],
  "default": "application/x-www-form-urlencoded"
}
```

#### Body Parameters

- **id_user** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "87"
  ],
  "default": "87"
}
```
- **sessionID** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "8758873590b28669.99489364"
  ],
  "default": "8758873590b28669.99489364"
}
```
- **id_searchedUser** should respect the following schema:

```
{
  "type": "string",
  "enum": [
    "22"
  ],
  "default": "22"
}
```

## References

