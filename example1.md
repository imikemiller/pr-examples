### 🔗 Github issue

#269 

### Description

We need to validate the fields values changed from workflow steps before save a complete draft.
We need validate a group of fields in a splited form.

You can see more details about it in #269 description

### Summary of Changes

- [x] Adjust validate service to validate a group of form fields
- [x] Create React hooks to validate group of a form fields
- [ ] Not validation when the first time when the form group loads.
- [ ] Fix the field height in order to has a save area to show the message error in a field.
- [ ] Adjust validate service to validate a complete workflow ( probably this is not complete at all and need adjust some cases, hooks and integration )


### Attachments

![validations](https://user-images.githubusercontent.com/1202463/66198190-2c0f5600-e69c-11e9-936e-82763cc5916c.gif)

Hooks not has leaks and the behavior of cpu is correct using useMemo and useCallback
![validationsCPU](https://user-images.githubusercontent.com/1202463/66198284-5f51e500-e69c-11e9-879b-57c69843c3b0.gif)

Inputs fields needs fix their height
![validationsFixHeight](https://user-images.githubusercontent.com/1202463/66198331-78f32c80-e69c-11e9-8306-4f59f2a5d6ad.gif)


### Testing Methodology

- added unit test into validation service
- check locally in app running under chrome


### Red Flags

Some works remain in order to finish all validation functionality.
