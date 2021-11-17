Useful SOQLs
============
**Payment SOQL**
```
SELECT Id, Amount__c, AuthorisationCode__c, Case__c, CaseId__c, CreatedDate, IncomeMgmtRcptNo__c, LastModifiedById, 
LastModifiedDate, Name, CreatedById, OwnerId, Payment_Method__c, SystemModstamp, WebPayment__c, RecordTypeId 
FROM Payment__c ORDER BY Id
```
try
 {
 final byte[] keyBytes = Base64.decode(secretKey);
 final SecretKey key = new SecretKeySpec(keyBytes, "HmacSHA256");
 final Mac hmac = Mac.getInstance(key.getAlgorithm());
hmac.init(key);
final byte[] bytesToHash = credentialsToHash.getBytes("UTF8");
 final byte[] hash = hmac.doFinal(bytesToHash);
return Base64.encodeBytes(hash);
 }
 catch (final Exception e)
 {
 throw new Exception(e);
 }
