**[MailSlurp JS](../README.md)**

> [Globals](../README.md) / UpdateInboxOptions

# Interface: UpdateInboxOptions

Options for updating inbox properties

**`export`** 

**`interface`** UpdateInboxOptions

## Hierarchy

* **UpdateInboxOptions**

## Index

### Properties

* [description](updateinboxoptions.md#description)
* [expiresAt](updateinboxoptions.md#expiresat)
* [favourite](updateinboxoptions.md#favourite)
* [name](updateinboxoptions.md#name)
* [tags](updateinboxoptions.md#tags)

## Properties

### description

• `Optional` **description**: string

*Defined in [src/generated/api.ts:5428](https://github.com/mailslurp/mailslurp-client/blob/730b817/src/generated/api.ts#L5428)*

Description of an inbox for labelling and searching purposes

**`memberof`** UpdateInboxOptions

___

### expiresAt

• `Optional` **expiresAt**: Date

*Defined in [src/generated/api.ts:5434](https://github.com/mailslurp/mailslurp-client/blob/730b817/src/generated/api.ts#L5434)*

Inbox expiration time. When, if ever, the inbox should expire and be deleted. If null then this inbox is permanent and the emails in it won't be deleted. This is the default behavior unless expiration date is set. If an expiration date is set and the time is reached MailSlurp will expire the inbox and move it to an expired inbox entity. You can still access the emails belonging to it but it can no longer send or receive email.

**`memberof`** UpdateInboxOptions

___

### favourite

• `Optional` **favourite**: boolean

*Defined in [src/generated/api.ts:5440](https://github.com/mailslurp/mailslurp-client/blob/730b817/src/generated/api.ts#L5440)*

Is the inbox a favorite inbox. Make an inbox a favorite is typically done in the dashboard for quick access or filtering

**`memberof`** UpdateInboxOptions

___

### name

• `Optional` **name**: string

*Defined in [src/generated/api.ts:5446](https://github.com/mailslurp/mailslurp-client/blob/730b817/src/generated/api.ts#L5446)*

Name of the inbox and used as the sender name when sending emails .Displayed in the dashboard for easier search

**`memberof`** UpdateInboxOptions

___

### tags

• `Optional` **tags**: Array\<string>

*Defined in [src/generated/api.ts:5452](https://github.com/mailslurp/mailslurp-client/blob/730b817/src/generated/api.ts#L5452)*

Tags that inbox has been tagged with. Tags can be added to inboxes to group different inboxes within an account. You can also search for inboxes by tag in the dashboard UI.

**`memberof`** UpdateInboxOptions
