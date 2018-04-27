---
title: "Procedure Object (ADOX)"
 
 
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: reference
  
localization_priority: Normal
ms.assetid: d5fcf0fe-f59f-e114-dc11-515f11c2a2c1

---

# Procedure Object (ADOX)

Represents a stored procedure. When used in conjunction with the ADO [Command](command-object-ado.md) object, the **Procedure** object can be used for adding, deleting, or modifying stored procedures. 
  
## Remarks

The **Procedure** object allows you to create a stored procedure without having to know or use the provider's "CREATE PROCEDURE" syntax. 
  
With the properties of a **Procedure** object, you can: 
  
- Identify the procedure with the [Name](name-property-adox.md) property. 
    
- Specify the ADO **Command** object that can be used to create or execute the procedure with the [Command](command-property-adox.md) property. 
    
- Return date information with the [DateCreated](datecreated-property-adox.md) and [DateModified](datemodified-property-adox.md) properties. 
    
