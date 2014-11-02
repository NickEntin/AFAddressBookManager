AFAddressBookManager
====================

Get contacts from iOS Address Book by their phone numbers and email addresses. Works on iOS 6+.

## Installation

Copy all files from AFAddressBookManager folder to your project and add the [Address Book framework](http://developer.apple.com/library/ios/#documentation/AddressBook/Reference/AddressBook_iPhoneOS_Framework/).

## Usage

Import `AFAddressBookManager.h` in the class where you want to use it.

### Available methods

Get name (first and last) of contact by phone number:
```objectivec
+ (NSString *)nameForContactWithPhoneNumber:(NSString *)phoneNumber;
```

Get photo of contact by phone number:
```objectivec 
+ (UIImage *)photoForContactWithPhoneNumber:(NSString *)phoneNumber;
```

Get name (first and last) of contact by email address:
```objectivec
+ (NSString *)nameForContactWithEmailAddress:(NSString *)emailAddress;
```

Get photo of contact by email address:
```objectivec 
+ (UIImage *)photoForContactWithEmailAddress:(NSString *)emailAddress;
```
