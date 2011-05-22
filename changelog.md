# Bag of Tricks Change Log #

## v1.0.5 ##
* A mountain of changes to `ObservableCollectionPlus<T>`
  * Added `Reset` method - *Closes #21*
  * Made sort methods safe - *Closes #22*
  * Added `MultiUpdateActive`
  * Changed the location of the call to protected `AfterMultiUpdate` to before raising reset

## v1.0.4 ##
* A mountain of clean-up in demo and test code
* Added `WatchProperty` extension method to `Extensions`
* **NEW** `PropertyChangeWatcher` - *Issue #16*
* Added some usage details to `InstanceFactory`
* Added `Util.ThrowUnless`
* `Extensions.GetCustomAttributes` -> change param `MemberInfo` to more generic `ICustomAttributeProvider` - *Issue #19*
* Added `AddRange` to `ObservableCollectionPlus<T>` - *Issues # 17*
* Some work to get Windows Phone 7 projects to load, although I've hit a snag with sharing generic.xaml between SL4 and Phone - progress towards *Issue #18*

## v1.0.3 ##
* Much smarter implementation of `Util.GetHashCode`
* Added `ClearErrors` to `DataErrorHelper`
* Moved the `targets` files
* Removed `[DataContract]` from `Changeable` - and cried that serialization support in Silverlight wasn't more flexible
* `AsyncValue`: added `LoadCommand` property and `LoadError` event - *Closes #10*