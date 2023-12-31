# [Lonica CSS](https://github.com/allencasul/Lonica) ![](https://img.shields.io/github/package-json/v/allencasul/Lonica) ![](https://img.shields.io/github/repo-size/allencasul/lonica?logo=github&color=yellow) ![](https://img.shields.io/jsdelivr/gh/hm/allencasul/lonica?color=orange) ![](https://img.shields.io/npm/dm/lonica?logo=npm&color=D02222) ![Github](https://img.shields.io/github/stars/allencasul/lonica?logo=github&color=6249EF) ![Github](https://img.shields.io/github/license/allencasul/Lonica?logo=Github)



An open-source design system framework that provides access to pre-built class components to quickly build modern web apps or use built-in utility classes to write custom CSS directly inside your markup. "Lonica" means source of happiness and beauty.

<img src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/gif%2Fhappiness.gif?alt=media&token=7fe57708-8ba0-45d9-b385-d6ce1bd16472" style="max-width:100%;" width="360">

## Installation

### Utilizing Framework via CDN

```sh
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/allencasul/lonica@cd9c596efc17048a2831fe3183c8b8860a8a90f6/css/cdn/lonica.css" integrity="sha256-E1S8yAbnRZ6uM4sA6NMSgTyoDsdK1ZCjBYF3lqXqv6Q=" crossorigin="anonymous">
  <script src="https://kit.fontawesome.com/1e8d61f212.js"></script>
</head>
```


Installing Lonica CSS

### Utilizing Framework via NPM

```sh
npm install lonica@latest
```


Overview:

## Framework Description

It is designed to simplify the process of building websites and applications by providing a set of pre-designed UI elements, layout structures, and reusable components that can be easily customized to fit specific project requirements. Lonica CSS Framework comes with a simple and intuitive Documentation, making it easy for both beginners and experienced developers to use it. Its responsive nature allows it to adapt to different screen sizes, making it ideal for building mobile-first web applications.

## Browser Support

- Chrome
- Edge
- Firefox
- Opera & any modern browser



### HTML Template

Create index.html file, and copy paste the boilerplate below.

```sh
<!DOCTYPE html>
<html lang="en-US">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="initial-scale=1, width=device-width, viewport-fit=cover"/>
  <meta name="color-scheme" content="light"/>
  <meta name="theme-color" content="#7542F1"/>
  <meta name="description" content="Lonica CSS Framework, your front-end development partner."/>
  <meta name="keywords" content="Lonica CSS Framework, lonica"/>
  <title>Lonica: Modern CSS Framework</title>
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/1e8d61f212.js"></script>
</head>
<body>
  <!--APP BAR-->

  <!--DROP DOWN MENU-->

  <!--FLOATING ACTION BUTTON-->

  <!--BOTTOM NAVIGATION BAR-->

  <!--SEARCH-->

  <!--BOTTOM SHEET DIALOG-->

  <!--SIDE BAR-->

  <!--ALERT DIALOG-->

  <!--TOAST-->

  <!--CARD-->

  <!--PRELOADER-->
  <div class="primary-preloader-overlay" id="primaryPreloaderOverlay">
    <div class="primary-preloader-container">
      <div class="primary-preloader-content-container">
        <div class="primary-preloader">

        </div>
      </div>
    </div>
  </div>
</body>
</html>
```

### CSS Template

Create style.css file, and copy paste the code below.

```sh
/* lonica | Under MIT License | github.com/allencasul/lonica */

/*--------- Utilities ---------*/
@import 'node_modules/lonica/css/utilities/utilities.min.css';

/*--------- Components ---------*/
@import 'node_modules/lonica/css/components/preloader.min.css';
@import 'node_modules/lonica/css/components/app-bar.min.css';
@import 'node_modules/lonica/css/components/side-bar.min.css';
@import 'node_modules/lonica/css/components/floating-action-button.min.css';
@import 'node_modules/lonica/css/components/bottom-navigation-bar.min.css';
@import 'node_modules/lonica/css/components/drop-down-menu.min.css';
@import 'node_modules/lonica/css/components/alert-dialog.min.css';
@import 'node_modules/lonica/css/components/bottom-sheet-dialog.min.css';
@import 'node_modules/lonica/css/components/toast.min.css';
@import 'node_modules/lonica/css/components/card.min.css';
@import 'node_modules/lonica/css/components/input.min.css';
@import 'node_modules/lonica/css/components/checkbox.min.css';
@import 'node_modules/lonica/css/components/button.min.css';
@import 'node_modules/lonica/css/components/stepper.min.css';
@import 'node_modules/lonica/css/components/table.min.css';  
```


### Utilizing Components

Use all available pre-made components below:

### Preloader

```sh
<div class="primary-preloader-overlay" id="primaryPreloaderOverlay">
  <div class="primary-preloader-container">
    <div class="primary-preloader-content-container">
      <div class="primary-preloader">

      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="secondary-preloader-overlay" id="secondaryPreloaderOverlay">
  <div class="secondary-preloader-container">
    <div class="secondary-preloader-content-container">
      <div class="secondary-preloader">

      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="tertiary-preloader-overlay" id="tertiaryPreloaderOverlay">
  <div class="tertiary-preloader-container">
    <div class="tertiary-preloader-content-container">
      <div class="tertiary-preloader">

      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="quaternary-preloader-overlay" id="quaternaryPreloaderOverlay">
  <div class="quaternary-preloader-container">
    <div class="quaternary-preloader-content-container">
      <div class="quaternary-preloader">

      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="quinary-preloader-overlay" id="quinaryPreloaderOverlay">
  <div class="quinary-preloader-container">
    <div class="quinary-preloader-content-container">
      <div class="quinary-preloader">
        <img class="quinary-pulse-gif" src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/gif%2Fpulse.gif?alt=media&token=050845aa-4a5c-4262-b214-2aaae48c2935">
      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="senary-preloader-overlay" id="senaryPreloaderOverlay">
  <div class="senary-preloader-container">
    <div class="senary-preloader-content-container">
      <div class="senary-preloader">

      </div>
      <div class="senary-preloader-text">
        Loading, please wait...
      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="septenary-preloader-overlay" id="septenaryPreloaderOverlay">
  <div class="septenary-preloader-container">
    <div class="septenary-preloader-text">Processing...</div>
    <div class="septenary-preloader-content-container">
      <div class="septenary-preloader">

      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="octonary-preloader-overlay" id="octonaryPreloaderOverlay">
  <div class="octonary-preloader-container">
    <div class="octonary-preloader-content-container">
      <div class="octonary-preloader">

      </div>
    </div>
  </div>
</div>
```

### App Bar

```sh
<div class="primary-app-bar-container background-color-primary">
  <div class="primary-app-bar-content-container">
    <div class="primary-app-bar-left-container">
      <div class="primary-app-bar-left-content-container">
        <div class="bar-container" id="showSideBarComponent" title="Menu">
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
        </div>
      </div>
      <div class="app-bar-title color-white">Home</div>
    </div>
    <div class="primary-app-bar-right-container">
      <div class="primary-app-bar-right-content-container" id="showDropdownMenuComponent" title="Dropdown">
        <i class="fa-solid fa-ellipsis-v app-bar-icon color-white"></i>
      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="secondary-app-bar-container background-color-primary">
  <div class="secondary-app-bar-content-container">
    <div class="secondary-app-bar-left-container">
      <div class="secondary-app-bar-left-content-container">
        <div class="bar-container" id="showSideBarComponent" title="Menu">
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
        </div>
      </div>
      <div class="app-bar-title color-white">Home</div>
    </div>
    <div class="secondary-app-bar-right-container">
      <div class="secondary-app-bar-right-content-container penultimate" id="showSearchComponent" title="Search">
        <i class="fa-solid fa-search app-bar-icon color-white"></i>
      </div>
      <div class="secondary-app-bar-right-content-container" id="showDropdownMenuComponent" title="Dropdown">
        <i class="fa-solid fa-ellipsis-v app-bar-icon color-white"></i>
      </div>
    </div>
  </div>
</div> 

------------------------------------------------------------------

<div class="tertiary-app-bar-container background-color-primary">
  <div class="tertiary-app-bar-content-container">
    <div class="tertiary-app-bar-left-container">
      <div class="tertiary-app-bar-left-content-container">
        <div class="bar-container" id="showSideBarComponent" title="Menu">
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
        </div>
      </div>
      <div class="app-bar-title color-white">Home</div>
    </div>
    <div class="tertiary-app-bar-right-container">
      <div class="tertiary-app-bar-right-content-container" id="showDropdownMenuComponent" title="Account">
        <img class="tertiary-app-bar-right-content-image" src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Ffounder.webp?alt=media&token=12adc7a0-76a4-4cf1-980f-38d3afd61ff4" alt="profile-photo">
      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="quaternary-app-bar-container background-color-primary">
  <div class="quaternary-app-bar-content-container">
    <div class="quaternary-app-bar-left-container">
      <div class="quaternary-app-bar-left-content-container">
        <div class="bar-container" id="showSideBarComponent" title="Menu">
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
          <div class="bar background-color-white"></div>
        </div>
      </div>
      <div class="app-bar-title color-white">Home</div>
    </div>
    <div class="quaternary-app-bar-right-container">
      <div class="quaternary-app-bar-right-content-container penultimate" id="showSearchComponent" title="Search">
        <i class="fa fa-search app-bar-icon color-white"></i>
      </div>
      <div class="quaternary-app-bar-right-content-container" id="showDropdownMenuComponent" title="Dropdown">
        <i class="fa fa-ellipsis-v app-bar-icon color-white"></i>
      </div>
    </div>
  </div>
  <div class="quaternary-app-bar-tab-container">
    <div class="quaternary-app-bar-tab-content-container">
      <div class="quaternary-app-bar-tab-content color-white font-size-small cursor-pointer">
        <div class="quaternary-app-bar-tab">
          <i class="fa fa-compass app-bar-icon"></i>
          EXPLORE
        </div>
        <div class="quaternary-app-bar-tab-content-horizontal-line background-color-white"></div>
      </div>
      <div class="quaternary-app-bar-tab-content color-disabled font-size-small cursor-pointer">
        <div class="quaternary-app-bar-tab">
          <i class="fa fa-map app-bar-icon"></i>
          TRIPS
        </div>
        <div class="quaternary-app-bar-tab-content-horizontal-line background-color-transparent"></div>
      </div>
    </div>
  </div>
</div>
```

### Side Bar

```sh
<div class="primary-side-bar-overlay background-color-overlay" id="primarySideBarOverlay"></div>
<div class="primary-side-bar-container background-color-white" id="primarySideBarContainer">
  <div class="primary-side-bar-content-container">

  </div>
</div>

------------------------------------------------------------------

<div class="secondary-side-bar-container w-4-point-5-rem h-100-vh background-color-white box-shadow-primary">
  <div class="secondary-side-bar-content-container center-absolute display-grid place-content-center row-gap-3-rem">
    <i class="fa-solid fa-home color-primary font-size-large cursor-pointer" title="Home"></i>
    <i class="fa-regular fa-comment-alt color-toast font-size-large cursor-pointer" title="Chat"></i>
    <i class="fa-regular fa-user color-toast font-size-large cursor-pointer" title="Profile"></i>
    <i class="fa-solid fa-share-alt color-toast font-size-large cursor-pointer" title="Share"></i>
  </div>
</div>
```

## Floating Action Button

```sh
<div class="primary-floating-action-button background-color-primary" id="showBottomSheetDialogComponent">
  <i class="fa-solid fa-plus primary-floating-action-button-icon color-white"></i>
</div>

------------------------------------------------------------------

<div class="secondary-floating-action-button background-color-primary" id="showBottomSheetDialogComponent">
  <i class="fa-solid fa-plus secondary-floating-action-button-icon color-white"></i>
  <div class="secondary-floating-action-button-text-title color-white">Compose</div>
</div>
```

## Bottom Navigation Bar

```sh
<div class="primary-bottom-navigation-bar-container background-color-white">
  <div class="primary-bottom-navigation-bar-content-container">
    <div class="primary-bottom-navigation-bar-content">
      <i class="fa-solid fa-home primary-bottom-navigation-bar-icon active"></i>
      <div class="primary-bottom-navigation-bar-text-title active">Home</div>
    </div>
    <div class="primary-bottom-navigation-bar-content">
      <i class="fa-solid fa-heart primary-bottom-navigation-bar-icon color-black"></i>
      <div class="primary-bottom-navigation-bar-text-title color-black">Favorites</div>
    </div>
    <div class="primary-bottom-navigation-bar-content" title="FAB">
      <div class="primary-bottom-navigation-floating-action-button background-color-primary" id="showBottomSheetDialogComponent">
        <i class="fa-solid fa-plus primary-floating-action-button-icon"></i>
      </div>
    </div>
    <div class="primary-bottom-navigation-bar-content">
      <i class="fa-solid fa-cart-shopping primary-bottom-navigation-bar-icon color-black"></i>
      <div class="primary-bottom-navigation-bar-text-title color-black">Cart</div>
    </div>
    <div class="primary-bottom-navigation-bar-content">
      <i class="fa-solid fa-user primary-bottom-navigation-bar-icon color-black"></i>
      <div class="primary-bottom-navigation-bar-text-title color-black">Account</div>
    </div>
  </div>
</div>      
```

## Drop Down Menu

```sh
<div class="primary-drop-down-menu-overlay background-color-transparent" id="primaryDropDownMenuOverlay">
  <div class="primary-drop-down-menu-container" id="primaryDropDownMenuContainer">
    <div class="primary-drop-down-menu-content-container">
      <i class="fa-solid fa-newspaper primary-drop-down-menu-icon"></i>
      <p class="primary-drop-down-menu-icon-text">Documentation</p>
    </div>
    <div class="primary-drop-down-menu-content-container">
      <i class="fa-solid fa-pager primary-drop-down-menu-icon"></i>
      <p class="primary-drop-down-menu-icon-text">Blog</p>
    </div>
    <div class="primary-drop-down-menu-content-container">
      <i class="fa-solid fa-phone primary-drop-down-menu-icon"></i>
      <p class="primary-drop-down-menu-icon-text">Contact</p>
    </div>
  </div> 
</div>
```

## Alert Dialog

```sh
<div class="primary-alert-dialog-overlay" id="primaryAlertDialogOverlay">
  <div class="primary-alert-dialog-container" id="primaryAlertDialogContainer">
    <div class="primary-alert-dialog-content-container">
      <div class="primary-alert-dialog-text-title">Delete Account?</div>
      <div class="primary-alert-dialog-text-description">This will delete your account permanently.</div>
      <div class="primary-alert-dialog-action-container">
        <div class="primary-alert-dialog-action" id="hideAlertDialog">Cancel</div>
        <div class="primary-alert-dialog-action color-danger">Delete</div>
      </div>
    </div>
  </div>
</div>
```

## Bottom Sheet Dialog

```sh
<div class="primary-bottom-sheet-dialog-overlay" id="primaryBottomSheetDialogOverlay"></div>
<div class="primary-bottom-sheet-dialog-container" id="primaryBottomSheetDialogContainer">
  <div class="primary-bottom-sheet-dialog-content-container">
    <div class="primary-bottom-sheet-dialog-content"><i class="fa-solid fa-share primary-bottom-sheet-dialog-content-icon"></i> Share</div>
    <div class="primary-bottom-sheet-dialog-content"><i class="fa-solid fa-link primary-bottom-sheet-dialog-content-icon"></i> Get link</div>
    <div class="primary-bottom-sheet-dialog-content"><i class="fa-solid fa-pencil primary-bottom-sheet-dialog-content-icon"></i> Edit</div>
    <div class="primary-bottom-sheet-dialog-content"><i class="fa-solid fa-trash primary-bottom-sheet-dialog-content-icon"></i> Delete</div>
  </div>
</div>

------------------------------------------------------------------

<div class="secondary-bottom-sheet-dialog-overlay" id="secondaryBottomSheetDialogOverlay"></div>
<div class="secondary-bottom-sheet-dialog-container" id="secondaryBottomSheetDialogContainer">
  <div class="secondary-bottom-sheet-dialog-content-container">
    <div class="secondary-bottom-sheet-dialog-title">Options</div>
      <div class="secondary-bottom-sheet-dialog-content"><i class="fa-solid fa-share secondary-bottom-sheet-dialog-content-icon"></i> Share</div>
      <div class="secondary-bottom-sheet-dialog-content"><i class="fa-solid fa-link secondary-bottom-sheet-dialog-content-icon"></i> Get link</div>
      <div class="secondary-bottom-sheet-dialog-content"><i class="fa-solid fa-pencil secondary-bottom-sheet-dialog-content-icon"></i> Edit</div>
    <div class="secondary-bottom-sheet-dialog-content"><i class="fa-solid fa-trash secondary-bottom-sheet-dialog-content-icon"></i> Delete</div>
  </div>
</div>
```

## Toast

```sh
<div class="primary-toast-container background-color-toast" id="primaryToastContainer">
  <div class="primary-toast-content-container">
    <div class="primary-toast-content color-white">
      <i class="fa-solid fa-circle-exclamation primary-toast-icon color-white"></i> File was uploaded
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="secondary-toast-container background-color-toast" id="secondaryToastContainer">
  <div class="secondary-toast-content-container">
    <div class="secondary-toast-content color-white">
      <i class="fa-solid fa-circle-exclamation secondary-toast-icon color-white"></i> File was uploaded
    </div>
  </div>
</div>
```

## Card

```sh
<div class="primary-card-container">
  <div class="primary-card-content-container">
    <div class="primary-card-content background-color-white">
      <img class="primary-card-image" src="https://source.unsplash.com/random" alt="random-image"/>
      <div class="primary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="primary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
    </div>
    <div class="primary-card-content background-color-white">
      <img class="primary-card-image" src="https://source.unsplash.com/featured" alt="random-image"/>
      <div class="primary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="primary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
    </div>
    <div class="primary-card-content background-color-white">
      <img class="primary-card-image" src="https://source.unsplash.com/featured/colors" alt="random-image"/>
      <div class="primary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="primary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
    </div>
    <div class="primary-card-content background-color-white">
      <img class="primary-card-image" src="https://source.unsplash.com/featured/clouds" alt="random-image"/>
      <div class="primary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="primary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
    </div>
    <div class="primary-card-content background-color-white">
      <img class="primary-card-image" src="https://source.unsplash.com/random/picture" alt="random-image"/>
      <div class="primary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="primary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
    </div>
  </div>
</div>
            
------------------------------------------------------------------

<div class="secondary-card-container background-color-white">
  <div class="secondary-card-content-container">
    <div class="secondary-card-top-container">
      <div class="secondary-card-top-image-container">
        <img class="secondary-card-top-image background-color-skeleton" src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Ffounder.webp?alt=media&token=12adc7a0-76a4-4cf1-980f-38d3afd61ff4" alt="profile-photo">
      </div>
      <div class="secondary-card-top-text-icon-container">
        <div class="secondary-card-top-text-container">
          <div class="secondary-card-top-text-title color-black font-size-medium">Lonica CSS Framework</div>
          <div class="secondary-card-top-text-description color-tost font-size-smaller">January 12, 2023</div>
        </div>
        <div class="secondary-card-top-icon-container" title="Option">
          <i class="fa-solid fa-ellipsis secondary-card-icon color-black"></i>
        </div>
      </div>
    </div>
    <div class="secondary-card-bottom-container">
      <img class="secondary-card-bottom-image h-15-point-5-rem" src="https://source.unsplash.com/random/portrait" alt="random-image"/>
      <div class="secondary-card-bottom-description color-toast font-size-medium">ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</div>
      <div class="secondary-card-bottom-text-icon-container">
        <div class="secondary-card-bottom-icon-container">
          <i class="fa-solid fa-heart secondary-card-icon color-love" title="Heart Post"></i>
          <i class="fa-solid fa-thumbs-up secondary-card-icon color-toast" title="Like Post"></i>
          <i class="fa-solid fa-share secondary-card-icon color-toast" title="Share Post"></i>
        </div>
        <div class="secondary-card-bottom-text-container color-enterprise-black font-size-medium"><i class="fa-solid fa-comment-dots secondary-card-icon color-toast" title="Comment"></i></div>
      </div>
    </div>
  </div>
</div>

------------------------------------------------------------------

<div class="tertiary-card-container">
  <div class="tertiary-card-content-container">
    <div class="tertiary-card-content background-color-white">
      <img class="tertiary-card-image" src="https://source.unsplash.com/random" alt="random-image"/>
      <div class="tertiary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="tertiary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
      <div class="tertiary-card-content-bottom-container">
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Explore</div>
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Share</div>
      </div>
    </div>
    <div class="tertiary-card-content background-color-white">
      <img class="tertiary-card-image" src="https://source.unsplash.com/random/people" alt="random-image"/>
      <div class="tertiary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="tertiary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
      <div class="tertiary-card-content-bottom-container">
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Explore</div>
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Share</div>
      </div>
    </div>
    <div class="tertiary-card-content background-color-white">
      <img class="tertiary-card-image" src="https://source.unsplash.com/random/clouds" alt="random-image"/>
      <div class="tertiary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="tertiary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
      <div class="tertiary-card-content-bottom-container">
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Explore</div>
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Share</div>
      </div>
    </div>
    <div class="tertiary-card-content background-color-white">
      <img class="tertiary-card-image" src="https://source.unsplash.com/random/colors" alt="random-image"/>
      <div class="tertiary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="tertiary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
      <div class="tertiary-card-content-bottom-container">
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Explore</div>
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Share</div>
      </div>
    </div>
    <div class="tertiary-card-content background-color-white">
      <img class="tertiary-card-image" src="https://source.unsplash.com/random/woman" alt="random-image"/>
      <div class="tertiary-card-title color-black font-size-medium color-black">Top 10 Best Photos</div>
      <div class="tertiary-card-description color-toast font-size-medium">
        ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </div>
      <div class="tertiary-card-content-bottom-container">
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Explore</div>
        <div class="tertiary-card-content-bottom-text font-size-small font-weight-700 color-primary">Share</div>
      </div>
    </div>
  </div>
</div>
```


## Stepper

```sh
<div class="primary-stepper-container">
  <div class="primary-steppper-content-container">
    <div class="primary-steppper-content">
      <div class="primary-stepper-circle w-3-rem h-3-rem background-color-active-primary border-radius-senary color-white font-size-large display-grid place-content-center">
        <i class="fa-solid fa-check color-white font-size-large"></i>
      </div>
      <div class="primary-stepper-text-container">
        <div class="primary-stepper-title color-active-primary  font-size-large">Order Placed</div>
        <div class="primary-stepper-description color-toast font-size-small">Your order has been placed</div>
      </div>
    </div>
    <div class="primary-steppper-content">
      <div class="primary-stepper-circle w-3-rem h-3-rem background-color-disabled border-radius-senary color-white font-size-large display-grid place-content-center">
        2 
      </div>
      <div class="primary-stepper-text-container">
        <div class="primary-stepper-title color-black  font-size-large">Preparing</div>
        <div class="primary-stepper-description color-toast font-size-small">Your order is being prepared</div>
      </div>
    </div>
    <div class="primary-steppper-content">
      <div class="primary-stepper-circle w-3-rem h-3-rem background-color-disabled border-radius-senary color-white font-size-large display-grid place-content-center">
        3 
      </div>
      <div class="primary-stepper-text-container">
        <div class="primary-stepper-title color-black  font-size-large">On the way</div>
        <div class="primary-stepper-description color-toast font-size-small">Your order is being shipped</div>
      </div>
    </div>
    <div class="primary-steppper-content">
      <div class="primary-stepper-circle w-3-rem h-3-rem background-color-disabled border-radius-senary color-white font-size-large display-grid place-content-center">
        4 
      </div>
      <div class="primary-stepper-text-container">
        <div class="primary-stepper-title color-black  font-size-large">Delivered</div>
        <div class="primary-stepper-description color-toast font-size-small">Your order was delivered successfully</div>
      </div>
    </div>
  </div>
</div>
```

## Input 

```sh
<div class="primary-input-container">
  <div class="primary-input-content-container">
    <i class="fa-solid fa-search primary-input-icon color-primary"></i>
    <input type="text" class="primary-input background-color-white color-black font-size-medium" placeholder="Search..." autocomplete="off">
  </div>
  <hr class="primary-input-line border-color-primary">
</div>
```

## Checkbox

```sh
<div class="primary-checkbox-container">
  <input class="primary-checkbox" type="checkbox">
  <div class="primary-checkbox-description color-black font-size-small">I agree to the <a class="font-size-small color-primary" href="https://lonica.com/privacy-policy" target="-blank">Privacy Policy</a>.</div>
</div>

------------------------------------------------------------------

<div class="secondary-checkbox-container">
  <input class="secondary-checkbox" id="switch" type="checkbox" aria-label="switch"/>
  <label class="secondary-checkbox-label" for="switch">
    <div class="secondary-checkbox-ball">
    
    </div>
  </label>
</div>
```

## Button 

```sh
<button class="primary-button background-color-primary font-size-medium color-white border-radius-secondary display-flex column-gap-1-rem">
  Login <i class="fa-solid fa-sign-in primary-button-icon color-white"></i>
</button>
```

## Table 

```sh
<div class="primary-table-container">
  <div class="primary-table-content-container">
    <table>
      <thead>
        <tr>
          <th>Country</th>
          <th>Nationality</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Philippines</td>
          <td>Filipino</td>
        </tr>
        <tr>
          <td>Korea</td>
          <td>Korean</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
```


## Chip

```sh
<div class="primary-chip-container background-color-even">
  <div class="primary-chip-content-container color-toast">
    <i class="fa-solid fa-user-circle font-size-extra-large active"></i>
    Avatar Chip
    <i class="fa-solid fa-circle-xmark font-size-medium color-gray" title="Remove"></i>
  </div>
</div>

------------------------------------------------------------------

<div class="secondary-chip-container background-color-odd">
  <div class="secondary-chip-content-container color-toast">
    <img class="secondary-chip-image" src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Ffounder.webp?alt=media&token=12adc7a0-76a4-4cf1-980f-38d3afd61ff4" alt="profile-photo" title="View Profile">
    Allen Charls Casul
    <i class="fa-solid fa-circle-xmark font-size-medium color-gray" title="Remove"></i>
  </div>
</div>
```


### Lonica CSS Utilities

Use built-in utility classes to write custom CSS directly inside your markup.



## Width

```sh
Width in Percentage 1-100%

w-10-point-5-pct   =   { width: 10.5%; }
    
w-100-pct   =   { width: 100%; }

------------------------------------------------------------------

Width in Rem 1-100rem

w-10-point-5-rem   =   { width: 10.5rem; }
    
w-100-rem   =   { width: 100rem; }

------------------------------------------------------------------

Width in Viewport Width 1-100vw

w-10-point-5-vw   =   { width: 10.5vw; }
    
w-100-vw   =   { width: 100vw; }

------------------------------------------------------------------

Width Fit Content

w-fit-content   =   { width: fit-content; }

------------------------------------------------------------------

Width Auto

w-auto   =   { width: auto; }

------------------------------------------------------------------

Max Width

max-w-100-pct   =   { max-width: 100%; }
```


## Height

```sh
Height in Percentage 1-100%

h-10-point-5-pct   =   { height: 10.5%; }
    
h-100-pct   =   { height: 100%; }

------------------------------------------------------------------

Height in Rem 1-100rem

h-10-point-5-rem   =   { height: 10.5rem; }
    
h-100-rem   =   { height: 100rem; }

------------------------------------------------------------------

Height in Viewport Height 1-100vh

w-10-point-5-vh   =   { height: 10.5vh; }
    
w-100-vh   =   { height: 100vh; }

------------------------------------------------------------------

Height Fit Content

h-fit-content   =   { height: fit-content; }

------------------------------------------------------------------

Height Auto

h-auto   =   { height: auto; }
```


## Margin

```sh
Margin in Rem 1-100rem

margin-auto   =   { margin: auto; }

------------------------------------------------------------------

margin-point-5-rem   =   { margin: .5rem; }   |   .5-100rem

------------------------------------------------------------------

margin-1-rem   =   { margin: 1rem; }   |   1-100

------------------------------------------------------------------

margin-top-1-rem   =   { margin-top: 1rem; }   |   1-100

------------------------------------------------------------------

margin-bottom-1-rem   =   { margin-bottom: 1rem; }   |   1-100

------------------------------------------------------------------

margin-left-1-rem   =   { margin-left: 1rem; }   |   1-100

------------------------------------------------------------------

margin-right-1-rem   =   { margin-right: 1rem; }   |   1-100
```


## Padding

```sh
Padding in Rem 1-100rem

padding-point-5-rem   =   { padding: .5rem; }   |   .5-100rem

------------------------------------------------------------------

padding-1-rem   =   { padding: 1rem; }   |   1-100

------------------------------------------------------------------

padding-top-1-rem   =   { padding-top: 1rem; }   |   1-100

------------------------------------------------------------------

padding-bottom-1-rem   =   { padding-bottom: 1rem; }   |   1-100

------------------------------------------------------------------

padding-left-1-rem   =   { padding-left: 1rem; }   |   1-100

------------------------------------------------------------------

padding-right-1-rem   =   { padding-right: 1rem; }   |   1-100
```


## Top

```sh
Top in Rem 1-100rem

top-zero   =   { top: 0; }   |   0-100rem

------------------------------------------------------------------

top-point-5-rem   =   { top: .5rem; }   |   .5-100rem

------------------------------------------------------------------

top-1-rem   =   { top: 1rem; }   |   1-100
```


## Bottom

```sh
Bottom in Rem 1-100rem

bottom-zero   =   { bottom: 0; }   |   0-100rem

------------------------------------------------------------------

bottom-point-5-rem   =   { bottom: .5rem; }   |   .5-100rem

------------------------------------------------------------------

bottom-1-rem   =   { bottom: 1rem; }   |   1-100
```


## Left

```sh
Left in Rem 1-100rem

left-zero   =   { left: 0; }   |   0-100rem

------------------------------------------------------------------

left-point-5-rem   =   { left: .5rem; }   |   .5-100rem

------------------------------------------------------------------

left-1-rem   =   { left: 1rem; }   |   1-100
```


## Right

```sh
Right in Rem 1-100rem

right-zero   =   { right: 0; }   |   0-100rem

------------------------------------------------------------------

right-point-5-rem   =   { right: .5rem; }   |   .5-100rem

------------------------------------------------------------------

left-1-rem   =   { left: 1rem; }   |   1-100
```


## Position

```sh
text-align-center   =   { text-align: center; }

------------------------------------------------------------------
  
text-align-center   =   { text-align: center; }
  
------------------------------------------------------------------
  
text-align-start   =   { text-align: start; }

------------------------------------------------------------------
  
text-align-end   =   { text-align: end; }
  
------------------------------------------------------------------
  
text-align-left   =   { text-align: left; }
  
------------------------------------------------------------------

text-align-right   =   { text-align: right; }
  
------------------------------------------------------------------

center-absolute   =   { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); }
  
------------------------------------------------------------------

center-fixed   =   { position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%); }
  
------------------------------------------------------------------

position-absolute   =   { position: absolute; }
  
------------------------------------------------------------------

position-fixed   =   { position: fixed; }
  
------------------------------------------------------------------

position-relative   =   { position: relative; }
  
------------------------------------------------------------------

position-static   =   { position: static; }
  
------------------------------------------------------------------

position-sticky   =   { position: sticky; }
  
------------------------------------------------------------------

position-inherit   =   { position: inherit; }

------------------------------------------------------------------  

position-initial   =   { position: initial; }

------------------------------------------------------------------
  
position-unset   =   { position: unset; }

------------------------------------------------------------------
  
float-inline-end   =   { float: inline-end; }
  
------------------------------------------------------------------

float-inline-start   =   { float: inline-start; }

------------------------------------------------------------------
  
float-left   =   { float: left; }

------------------------------------------------------------------
  
float-right   =   { float: right; }

------------------------------------------------------------------
  
float-none   =   { float: none; }
```


## Flex

```sh
  
display-flex   =   { display: flex; }
  
------------------------------------------------------------------

align-items-center   =   { align-items: center; }
  
------------------------------------------------------------------

align-content-center   =   { align-content: center; }
  
------------------------------------------------------------------

justify-content-center   =   { justify-content: center; }
  
------------------------------------------------------------------

justify-content-start   =   { justify-content: start; }
  
------------------------------------------------------------------

justify-content-end   =   { justify-content: end; }
  
------------------------------------------------------------------

justify-content-left   =   { justify-content: left; }
  
------------------------------------------------------------------

justify-content-right   =   { justify-content: right; }
  
------------------------------------------------------------------

justify-content-space-around   =   { justify-content: space-around; }
  
------------------------------------------------------------------

justify-content-space-evenly   =   { justify-content: space-evenly; }
  
------------------------------------------------------------------

justify-content-space-between   =   { justify-content: space-between; }
  
------------------------------------------------------------------

flex-direction-column   =   { flex-direction: column; }
  
------------------------------------------------------------------

flex-direction-row   =   { flex-direction: row; }
  
------------------------------------------------------------------

flex-wrap-wrap   =   { flex-wrap: wrap }
  
------------------------------------------------------------------

flex-wrap-now-wrap   =   { flex-wrap: nowrap }
  
------------------------------------------------------------------

flex-wrap-reverse   =   { flex-wrap: wrap-reverse }
  
------------------------------------------------------------------

gap-point-5-rem   =   { gap: .5rem; }

gap-1-rem   =   { gap: 1rem; } | 1-10

------------------------------------------------------------------

column-gap-point-5-rem   =   { column-gap: .5rem; }

column-gap-1-rem   =   { column-gap: 1rem; }
  
------------------------------------------------------------------

row-gap-point-5-rem   =   { row-gap: .5rem; }

row-gap-1-rem   =   { row-gap: 1rem; }
  
------------------------------------------------------------------

columns-1   =   { columns: 1; }
  
------------------------------------------------------------------

break-inside-avoid   =   { break-inside: avoid; }
  
------------------------------------------------------------------

display-flex   =   { display: flex; }
  
------------------------------------------------------------------

align-items-center   =   { align-items: center; }
  
------------------------------------------------------------------

align-content-center   =   { align-content: center; }
  
------------------------------------------------------------------

justify-content-center   =   { justify-content: center; }
  
------------------------------------------------------------------

justify-content-start   =   { justify-content: start; }
  
------------------------------------------------------------------

justify-content-end   =   { justify-content: end; }
  
------------------------------------------------------------------

justify-content-left   =   { justify-content: left; }
  
------------------------------------------------------------------

justify-content-right   =   { justify-content: right; }
  
------------------------------------------------------------------

justify-content-space-around   =   { justify-content: space-around; }

------------------------------------------------------------------

justify-content-space-evenly   =   { justify-content: space-evenly; }
  
------------------------------------------------------------------

justify-content-space-between   =   { justify-content: space-between; }
  
------------------------------------------------------------------

flex-direction-column   =   { flex-direction: column; }
  
------------------------------------------------------------------

flex-direction-row   =   { flex-direction: row; }
  
------------------------------------------------------------------

flex-wrap-wrap   =   { flex-wrap: wrap }
  
------------------------------------------------------------------

flex-wrap-now-wrap   =   { flex-wrap: nowrap }
  
------------------------------------------------------------------

flex-wrap-reverse   =   { flex-wrap: wrap-reverse }

------------------------------------------------------------------

gap-point-5-rem   =   { gap: .5rem; }

gap-1-rem   =   { gap: 1rem; } | 1-10
  
------------------------------------------------------------------

column-gap-point-5-rem   =   { column-gap: .5rem; }

column-gap-1-rem   =   { column-gap: 1rem; }
  
------------------------------------------------------------------

row-gap-point-5-rem   =   { row-gap: .5rem; }

row-gap-1-rem   =   { row-gap: 1rem; }
  
------------------------------------------------------------------

columns-1   =   { columns: 1; } | 1-10
  
------------------------------------------------------------------

break-inside-avoid   =   { break-inside: avoid; }
```


## Grid

```sh
  
display-grid   =   { display: grid; }
  
------------------------------------------------------------------

place-content-center   =   { place-content: center; }
  
------------------------------------------------------------------

place-items-center   =   { place-items: center; }
  
------------------------------------------------------------------

place-content-start   =   { place-content: start; }
  
------------------------------------------------------------------

place-content-end   =   { place-content: end; }
  
------------------------------------------------------------------

place-content-left   =   { place-content: left; }
  
------------------------------------------------------------------

place-content-right   =   { place-content: right; }

------------------------------------------------------------------

gap-point-5-rem   =   { gap: .5rem; }

gap-1-rem   =   { gap: 1rem; } | 1-10

------------------------------------------------------------------

column-gap-point-5-rem   =   { column-gap: .5rem; }

column-gap-1-rem   =   { column-gap: 1rem; }
  
------------------------------------------------------------------

row-gap-point-5-rem   =   { row-gap: .5rem; }

row-gap-1-rem   =   { row-gap: 1rem; }
  
------------------------------------------------------------------

columns-1   =   { columns: 1; } | 1-10
  
------------------------------------------------------------------

break-inside-avoid   =   { break-inside: avoid; }
  
------------------------------------------------------------------

display-grid   =   { display: grid; }
  
------------------------------------------------------------------

place-content-center   =   { place-content: center; }
  
------------------------------------------------------------------

place-items-center   =   { place-items: center; }
  
------------------------------------------------------------------ 

place-content-start   =   { place-content: start; }
  
------------------------------------------------------------------ 

place-content-end   =   { place-content: end; }
  
------------------------------------------------------------------  

place-content-left   =   { place-content: left; }
  
------------------------------------------------------------------

place-content-right   =   { place-content: right; }
  
------------------------------------------------------------------

grid-temp-col-primary   =   { grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); }
  
------------------------------------------------------------------ 

grid-temp-col-secondary   =   { grid-template-columns: 50% 50%; }
  
------------------------------------------------------------------

grid-temp-col-tertiary   =   { grid-template-columns: 33% 33% 33%; }

------------------------------------------------------------------

grid-temp-col-quaternary   =   { grid-template-columns: 25% 25% 25% 25%; }

------------------------------------------------------------------

grid-temp-col-quinary   =   { grid-template-columns: 20% 20% 20% 20% 20%; }
  
------------------------------------------------------------------

column-gap-point-5-rem   =   { column-gap: .5rem; }

column-gap-1-rem   =   { column-gap: 1rem; }
  
------------------------------------------------------------------

row-gap-point-5-rem   =   { row-gap: .5rem; }

row-gap-1-rem   =   { row-gap: 1rem; }
  
------------------------------------------------------------------

columns-1   =   { columns: 1; } | 1-10
  
------------------------------------------------------------------

break-inside-avoid   =   { break-inside: avoid; }
```


## Font Size

```sh
font-size-super-small   =   { font-size: 10px; }

------------------------------------------------------------------

font-size-extra-small   =   { font-size: 12px; }

------------------------------------------------------------------

font-size-smaller   =   { font-size: 14px; }

------------------------------------------------------------------

font-size-small   =   { font-size: 15px; }

------------------------------------------------------------------

font-size-medium   =   { font-size: 16px; }

------------------------------------------------------------------

font-size-large   =   { font-size: 17px; }

------------------------------------------------------------------

font-size-larger   =   { font-size: 20px; }

------------------------------------------------------------------

font-size-extra-large   =   { font-size: 1.5rem; }

------------------------------------------------------------------

font-size-super-large   =   { font-size: 2rem; }

------------------------------------------------------------------

font-size-massive   =   { font-size: 2.5rem; }

------------------------------------------------------------------

font-size-super-massive   =   { font-size: 3rem; }

------------------------------------------------------------------

font-size-ton-618   =   { font-size: 3.5rem; }
```


## Font Weight

```sh
  
font-weight-bold   =   { font-weight: bold; }

------------------------------------------------------------------

font-weight-bolder   =   { font-weight: bolder; }

------------------------------------------------------------------

font-weight-lighter   =   { font-weight: lighter; }

------------------------------------------------------------------

font-weight-normal   =   { font-weight: normal; }

------------------------------------------------------------------

font-weight-100   =   { font-weight: 100; }

------------------------------------------------------------------

font-weight-200   =   { font-weight: 200; }

------------------------------------------------------------------

font-weight-300   =   { font-weight: 300; }

------------------------------------------------------------------

font-weight-400   =   { font-weight: 400; }

------------------------------------------------------------------

font-weight-500   =   { font-weight: 500; }

------------------------------------------------------------------

font-weight-600   =   { font-weight: 600; }

------------------------------------------------------------------

font-weight-700   =   { font-weight: 700; }

------------------------------------------------------------------

font-weight-800   =   { font-weight: 800; }

------------------------------------------------------------------

font-weight-900   =   { font-weight: 900; }
```


## Box Shadow

```sh
box-shadow-none   =   { box-shadow: none; }

------------------------------------------------------------------
box-shadow-primary   =   { box-shadow: var(--shadow-primary); }

------------------------------------------------------------------

box-shadow-secondary   =   { box-shadow: var(--shadow-secondary); }

------------------------------------------------------------------

box-shadow-tertiary   =   { box-shadow: var(--shadow-tertiary); }

------------------------------------------------------------------

box-shadow-quaternary   =   { box-shadow: var(--shadow-quaternary); }
```


## Border

```sh
border-none   =   { border: none; }

------------------------------------------------------------------

border-primary   =   { border: 1px solid var(--lightgray); }

------------------------------------------------------------------

border-secondary   =   { border: 2px solid var(--lightgray); }

------------------------------------------------------------------

border-tertiary   =   { border: 3px solid var(--lightgray); }
```


## Border Radius

```sh
border-radius-primary   =   { border-radius: 4px; }

------------------------------------------------------------------

border-radius-secondary   =   { border-radius: 6px; }

------------------------------------------------------------------

border-radius-tertiary   =   { border-radius: 8px; }

------------------------------------------------------------------

border-radius-quaternary   =   { border-radius: 10px; }

------------------------------------------------------------------

border-radius-quinary   =   { border-radius: 15px; }

------------------------------------------------------------------

border-radius-senary   =   { border-radius: 100px; }

------------------------------------------------------------------

border-radius-septenary   =   { border-radius: 50%; }
```


## Text Color

```sh
color-primary   =   { color: var(--primary); }

------------------------------------------------------------------

color-danger   =   { color: var(--danger); }

------------------------------------------------------------------
color-warning   =   { color: var(--warning); }

------------------------------------------------------------------

color-info   =   { color: var(--info); }

------------------------------------------------------------------

color-successful   =   { color: var(--successful); }

------------------------------------------------------------------

color-amethyst   =   { color: var(--amethyst); }
```


## Background Color

```sh
background-color-primary   =   { background-color: var(--primary); }

------------------------------------------------------------------

background-color-danger   =   { background-color: var(--danger); }

------------------------------------------------------------------
background-color-warning   =   { background-color: var(--warning); }

------------------------------------------------------------------

background-color-info   =   { background-color: var(--info); }

------------------------------------------------------------------

background-color-successful   =   { background-color: var(--successful); }

------------------------------------------------------------------

background-color-amethyst   =   { background-color: var(--amethyst); }
```


<img src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Fcolor-1.png?alt=media&token=8bc028a2-7c25-471a-887b-fe1559df908e" style="max-width:100%;" width="970">
<img src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Fcolor-2.png?alt=media&token=e8830126-3b9a-4526-a00b-f659a20fa5e6" style="max-width:100%;" width="970">
<img src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Fcolor-3.png?alt=media&token=5d1adebf-d850-4434-920e-a14765f052c8" style="max-width:100%;" width="970">
<img src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Fcolor-4.png?alt=media&token=13203dc7-9920-4087-b8c6-7ba082843877" style="max-width:100%;" width="970">
<img src="https://firebasestorage.googleapis.com/v0/b/lonica.appspot.com/o/img%2Fcolor-5.png?alt=media&token=7e125221-d776-4e84-b165-0c3222f885e2" style="max-width:100%;" width="970">


## Other

```sh

display-none  =  display-none { display: none }

display-block  =  display-block { display: block }

------------------------------------------------------------------

object-fit-cover  =  object-fit-cover { object-fit: cover }

object-fit-contain  =  object-fit-contain { object-fit: contain }

object-fit-fill  =  object-fit-fill { object-fit: fill }

------------------------------------------------------------------

primary-skeleton-loader  =  primary-skeleton-loader {
  animation: skeleton-loader 1.3s infinite;
  background: linear-gradient(90deg, var(--skeleton) 30%, f9f9f9 38%, f9f9f9 40%, var(--skeleton) 48%);
  background-size: 200% 100%;
  background-position: 100% 0;
}

@keyframes skeleton-loader {
  100% {
    background-position: -100% 0;
  }
}

------------------------------------------------------------------

secondary-skeleton-loader  =  secondary-skeleton-loader {
  animation: skeleton-loader 1.3s infinite;
  background: linear-gradient(120deg, var(--skeleton) 30%, f9f9f9 38%, f9f9f9 40%, var(--skeleton) 48%);
  background-size: 200% 100%;
  background-position: 100% 0;
}

@keyframes skeleton-loader {
  100% {
    background-position: -100% 0;
  }
}

------------------------------------------------------------------

active-shadow-primary  =  active-shadow-primary:active { box-shadow: var(--shadow-primary); }

------------------------------------------------------------------

hover-shadow-primary  =  hover-shadow-primary:hover { box-shadow: var(--shadow-primary); }

------------------------------------------------------------------

active-shadow-none  =  active-shadow-none:active { box-shadow: none; transition: none; }

------------------------------------------------------------------

hover-shadow-none  =  hover-shadow-none:hover { box-shadow: none; transition: none; }

------------------------------------------------------------------

color-active-primary  =  color-active-primary { color: var(--primary); }

------------------------------------------------------------------

background-color-active-primary  =  background-color-active-primary { background-color: var(--primary); }
```


## Licensing

Copyright holder Allen Charls Casul. Source Code is under [the MIT license](https://github.com/allencasul/lonica/blob/main/LICENSE).



