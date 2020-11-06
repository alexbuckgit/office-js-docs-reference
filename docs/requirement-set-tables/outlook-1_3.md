| Class | Fields | Description |
|:---|:---|:---|
|[AppointmentCompose](/javascript/api/outlook/outlook.appointmentcompose)|[close()](/javascript/api/outlook/outlook.appointmentcompose#close--)|Closes the current item that is being composed|
||[notificationMessages](/javascript/api/outlook/outlook.appointmentcompose#notificationmessages)|Gets the notification messages for an item.|
||[saveAsync(callback: (asyncResult: Office.AsyncResult<string>) => void)](/javascript/api/outlook/outlook.appointmentcompose#saveasync-callback--asyncresult-)|Asynchronously saves an item.|
||[saveAsync(options: Office.AsyncContextOptions, callback: (asyncResult: Office.AsyncResult<string>) => void)](/javascript/api/outlook/outlook.appointmentcompose#saveasync-options--callback--asyncresult-)|Asynchronously saves an item.|
|[AppointmentRead](/javascript/api/outlook/outlook.appointmentread)|[notificationMessages](/javascript/api/outlook/outlook.appointmentread#notificationmessages)|Gets the notification messages for an item.|
|[Body](/javascript/api/outlook/outlook.body)|[getAsync(coercionType: Office.CoercionType \| string, options?: Office.AsyncContextOptions, callback?: (asyncResult: Office.AsyncResult<string>) => void)](/javascript/api/outlook/outlook.body#getasync-coerciontype--options--callback--asyncresult-)|Returns the current body in a specified format.|
||[setAsync(data: string, options?: Office.AsyncContextOptions & CoercionTypeOptions, callback?: (asyncResult: Office.AsyncResult<void>) => void)](/javascript/api/outlook/outlook.body#setasync-data--options--callback--asyncresult-)|Replaces the entire body with the specified text.|
|[Mailbox](/javascript/api/outlook/outlook.mailbox)|[convertToEwsId(itemId: string, restVersion: MailboxEnums.RestVersion \| string)](/javascript/api/outlook/outlook.mailbox#converttoewsid-itemid--restversion-)|Converts an item ID formatted for REST into EWS format.|
||[convertToRestId(itemId: string, restVersion: MailboxEnums.RestVersion \| string)](/javascript/api/outlook/outlook.mailbox#converttorestid-itemid--restversion-)|Converts an item ID formatted for EWS into REST format.|
|[MessageCompose](/javascript/api/outlook/outlook.messagecompose)|[close()](/javascript/api/outlook/outlook.messagecompose#close--)|Closes the current item that is being composed|
||[notificationMessages](/javascript/api/outlook/outlook.messagecompose#notificationmessages)|Gets the notification messages for an item.|
||[saveAsync(callback: (asyncResult: Office.AsyncResult<string>) => void)](/javascript/api/outlook/outlook.messagecompose#saveasync-callback--asyncresult-)|Asynchronously saves an item.|
||[saveAsync(options: Office.AsyncContextOptions, callback: (asyncResult: Office.AsyncResult<string>) => void)](/javascript/api/outlook/outlook.messagecompose#saveasync-options--callback--asyncresult-)|Asynchronously saves an item.|
|[MessageRead](/javascript/api/outlook/outlook.messageread)|[notificationMessages](/javascript/api/outlook/outlook.messageread#notificationmessages)|Gets the notification messages for an item.|
|[NotificationMessageDetails](/javascript/api/outlook/outlook.notificationmessagedetails)|[icon](/javascript/api/outlook/outlook.notificationmessagedetails#icon)|A reference to an icon that is defined in the manifest in the `Resources` section.|
||[key](/javascript/api/outlook/outlook.notificationmessagedetails#key)|The identifier for the notification message.|
||[message](/javascript/api/outlook/outlook.notificationmessagedetails#message)|The text of the notification message.|
||[persistent](/javascript/api/outlook/outlook.notificationmessagedetails#persistent)|Specifies if the message should be persistent.|
||[type](/javascript/api/outlook/outlook.notificationmessagedetails#type)|Specifies the `ItemNotificationMessageType` of message.|
|[NotificationMessages](/javascript/api/outlook/outlook.notificationmessages)|[addAsync(key: string, JSONmessage: NotificationMessageDetails, options?: Office.AsyncContextOptions, callback?: (asyncResult: Office.AsyncResult<void>) => void)](/javascript/api/outlook/outlook.notificationmessages#addasync-key--jsonmessage--options--callback--asyncresult-)|Adds a notification to an item.|
||[getAllAsync(options?: Office.AsyncContextOptions, callback?: (asyncResult: Office.AsyncResult<NotificationMessageDetails[]>) => void)](/javascript/api/outlook/outlook.notificationmessages#getallasync-options--callback--asyncresult-)|Returns all keys and messages for an item.|
||[removeAsync(key: string, options?: Office.AsyncContextOptions, callback?: (asyncResult: Office.AsyncResult<void>) => void)](/javascript/api/outlook/outlook.notificationmessages#removeasync-key--options--callback--asyncresult-)|Removes a notification message for an item.|
||[replaceAsync(key: string, JSONmessage: NotificationMessageDetails, options?: Office.AsyncContextOptions, callback?: (asyncResult: Office.AsyncResult<void>) => void)](/javascript/api/outlook/outlook.notificationmessages#replaceasync-key--jsonmessage--options--callback--asyncresult-)|Replaces a notification message that has a given key with another message.|