# 0.6.0
* Updated to `bloc: ^1.0.0`
    * `bloc.state.listen` -> `bloc.listen`
    * `bloc.currentState` -> `bloc.state`
    * `dispatch` -> `add`
    * `dispose` -> `close`
* Documentation Updates.
* `Validators` -> `FieldBlocValidators`
* `ValidatorsError` -> `FieldBlocValidatorsErrors`
* Removed `isRequired` property from `FieldBloc` and `FieldBlocState`.

# 0.5.2
* Documentation Updates.
* Fixed a bug in `isValid` property of `fieldBlocState`.
* Prevented to update `FieldBloc.value` if is the same value and is validated.
* Improved `requiredTextFieldBloc` validator.

# 0.5.1
* Fixed a bug in `MultiSelectFieldBloc`.

# 0.5.0
* Dependency and Documentation Updates.
* Added `isValidating` property to `FieldBlocState`.
* Added `asyncValidators` property to `FieldBloc`.
* Added `asyncValidatorDebounceTime` property to `FieldBloc`.
* Added `addAsyncValidators` method to `FieldBloc`.
* Added `updateAsyncValidators` method to `FieldBloc`.
* Added `addError` method to `FieldBloc`.
* Added `subscribeToFieldBlocs` method to `FieldBloc`.

# 0.4.1
* Documentation Updates.

# 0.4.0
* Documentation Updates.
* Added Tests.
* Added `autoValidate` property to `FormBloc`.
* Added `InputFieldBloc<Value>`.
* Removed `FileFieldBloc`, now you can use `InputFieldBloc<File>`.
* Added `MultiSelectFieldBloc<Value>`.
* Added `error` property to `FieldBlocState`.
* Added `canShowError` property to `FieldBlocState`.
* Added `canShowProgress` property to `FieldBlocState`.
* Added `suggestions` property to `FieldBlocState`.
* Added `isRequired` property to `FieldBlocState`.
* Changes `TextFieldBloc<Error>` to `TextFieldBloc`.
* Added `valueToInt` property to `TextFieldBlocState`.
* Added `valueToDouble` property to `TextFieldBlocState`.
* Added `FormBlocDelegate`.

# 0.3.1

* Added `isCanceling` property to `FormBlocSubmitting`.

# 0.3.0

* Dependency and Documentation Updates.
* Added `submissionProgress` property to `FormBlocState`.
* Added `canSubmit` property to `FormBlocState`.
* Added `FormBlocSubmissionFailed` state to `FormBloc`.
* Added `FormBlocSubmissionCancelled` state to `FormBloc`.
* Added `cancelSubmission` event to `FormBloc`.
* Added `updateState` event to `FormBloc`.
* Added `onCancelSubmission` method to `FormBloc`.
* Added `FileFieldBloc`.

# 0.2.0

* Documentation Updates
# 0.1.0

* Initial Version of the library.
