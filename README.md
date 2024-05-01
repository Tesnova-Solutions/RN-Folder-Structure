# RN-Folder-Structure



## Folder Structure

Here is the folder structure to follow:

    src
	├── api
	│   ├── api.ts
	│   └── axios.ts
	├── assets
	│   ├── fonts
	│   │   ├── Inter-Bold.ttf
	│   │   ├── Inter-ExtraBold.ttf
	│   │   ├── Inter-Light.ttf
	│   │   ├── Inter-Medium.ttf
	│   │   ├── Inter-Regular.ttf
	│   │   └── Inter-SemiBold.ttf
	│   ├── icons
	│   │   └── upload.png
	│   └── logo.png
	├── components
	│   ├── common
	│   │   ├── InputDropDown
	│   │   │   ├── InputDropDown.styles.ts
	│   │   │   └── InputDropDown.tsx
	│   │   ├── appHeader
	│   │   │   ├── AppHeader.styles.ts
	│   │   │   └── AppHeader.tsx
	│   │   ├── appIcons
	│   │   │   └── AppIcons.tsx
	│   │   ├── appImage
	│   │   │   ├── AppImage.styles.ts
	│   │   │   └── AppImage.tsx
	│   │   ├── appInput
	│   │   │   ├── AppInput.styles.ts
	│   │   │   └── AppInput.tsx
	│   │   ├── appSpacer
	│   │   │   ├── AppSpacer.styles.ts
	│   │   │   └── AppSpacer.tsx
	│   │   ├── appText
	│   │   │   └── AppText.tsx
	│   │   ├── appView
	│   │   │   └── AppView.tsx
	│   │   ├── button
	│   │   │   ├── Button.styles.ts
	│   │   │   └── Button.tsx
	│   │   ├── checkBox
	│   │   │   ├── CheckBox.styles.ts
	│   │   │   └── CheckBox.tsx
	│   │   ├── popup
	│   │   │   ├── Popup.styles.ts
	│   │   │   └── Popup.tsx
	│   │   ├── thumbnail
	│   │   │   ├── Thumbnail.styles.ts
	│   │   │   └── Thumbnail.tsx
	│   │   └── toast
	│   │       ├── Toast.styles.ts
	│   │       └── Toast.tsx
	│   └── custom
	│       ├── actionModal
	│       │   ├── ActionModal.styles.ts
	│       │   └── ActionModal.tsx
	│       ├── bottomModal
	│       │   ├── BottomModal.styles.ts
	│       │   └── BottomModal.tsx
	│       ├── contentLoader
	│       │   └── FolderContentLoader.tsx
	│       ├── customBottomTab
	│       │   ├── CustomBottomTab.styles.ts
	│       │   └── CustomBottomTab.tsx
	│       ├── dropDown
	│       │   ├── DropDown.styles.ts
	│       │   └── DropDown.tsx
	├── constants
	│   ├── apiCodes.ts
	│   ├── appConsts.ts
	│   ├── appFonts.ts
	│   ├── appInfo.ts
	│   ├── appSizes.ts
	│   ├── colors.ts
	│   ├── demoData.ts
	│   ├── globalStyle.ts
	│   ├── icons.ts
	│   └── screenNames.ts
	├── helper
	│   ├── appHelper.ts
	│   ├── errorHelper.ts
	│   └── hexToRGBA.ts
	├── hooks
	│   ├── useApiHook.ts
	│   ├── useAppTheme.ts
	│   ├── useAppUser.ts
	├── navigation
	│   ├── BottomTabNavigator.tsx
	│   ├── MainNavigation.tsx
	│   └── services
	│       └── NavigationService.ts
	├── screens
	│   ├── accountSettings
	│   │   ├── AccountSettings.styles.ts
	│   │   ├── AccountSettings.tsx
	│   │   ├── Billing.tsx
	│   │   ├── Personal.tsx
	│   │   └── Security.tsx
	│   ├── auth
	│   │   ├── Auth.styles.ts
	│   │   ├── EmailVerification.tsx
	│   │   ├── Login.tsx
	│   │   ├── Plans.tsx
	│   │   ├── RestorePassword.tsx
	│   │   └── SignUp.tsx
	│   ├── team
	│   │   ├── Team.styles.ts
	│   │   └── Team.tsx
	│   └── users
	│       ├── Users.styles.ts
	│       └── Users.tsx
	├── store
	│   ├── appSlice.ts
	│   └── toastSlice.ts
	│   └── storage.ts
	└── types
	    ├── apiTypes.ts
	    ├── appTypes.ts
	    ├── authTypes.ts
	    ├── commonTypes.ts
