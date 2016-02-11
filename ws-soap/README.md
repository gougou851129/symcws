# Symantec Website Security Python library
For a fully-detailed API documentation, please go to https://developers.websecurity.symantec.com

#Changelog
##v1.4:
 - Forced TLSv1.2 connection, as Symantec blocks TLS1.0 and earlier.

##v1.3:
 - Added new API functions released in April 2015:
   QUERY:
       - GetModifiedOrderSummary
       - GetModifiedPreAuthOrderSummary
 - Added setApiVersion operation to make use of ApiVersion in ReqestHeaders.
##v1.2:
 - Added new API functions released world-wide in February 2015 including
   QUERY:
       - GetPreAuthOrdersByDateRange
       - GetPreAuthOrderByPartnerOrderID
   ORDER:
       - OrderPreAuthentication
       - ValidatePreAuthenticationData
 - Added new parameters to existing functions.
##v1.1:
 - Added Proxy support.
   Proxy can be set using:
       setProxy(url, port) 
   function.

## v1.0
Initial version 
