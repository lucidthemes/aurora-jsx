# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2025-12-10

### Changed

#### Features

##### ProductList

- reformat productList component to resolve eslint error of calling setState synchronously within an effect
- reformat hooks to resolve eslint error of calling setState synchronously within an effect
- reformat tests to resolve eslint error of calling setState synchronously within an effect

#### Root

- eslint config to better handle linting JS/JSX and test files

### Fixed

#### Components

##### Footer

- copyright link eslint error message of not having noreferrer

##### Form

- checkbox component eslint error message of assigned a value but never used

##### Header

- Search component eslint error message of calling hooks conditionally

##### Notification

- useNotification hook eslint error message of calling setState synchronously within an effect

#### Features

##### Account

- useOrders eslint error message of calling setState synchronously within an effect

##### BlogPost

- useSinglePost eslint error message of calling setState synchronously within an effect
- useNavigation eslint error message of calling setState synchronously within an effect
- useRelated eslint error message of calling setState synchronously within an effect
- useTags eslint error message of calling setState synchronously within an effect

##### Cart

- CouponForm eslint error message of calling hooks conditionally

##### Checkout

- useCheckout eslint error message of calling setState synchronously within an effect by removing unnecessary useEffect
- orderReceived useOrderReceived eslint error message of calling setState synchronously within an effect
- orderReceived Items component eslint error message of calling hooks conditionally
- orderReceived useItems hook eslint error message of calling hooks conditionally

##### ProductPost

- useSingleProduct eslint error message of calling setState synchronously within an effect
- useBreadcrumb eslint error message of calling setState synchronously within an effect
- useRelated eslint error message of calling setState synchronously within an effect
- useAddCartForm eslint error message of calling setState synchronously within an effect
- useVariations eslint error message of calling setState synchronously within an effect
- useList eslint error message of calling setState synchronously within an effect

##### SearchForm

- useSearchForm eslint error message of calling setState synchronously within an effect by removing unnecessary useEffect
- useSearchForm test to work with hook eslint error fix

## [1.0.13] - 2025-12-09

### Changed

- updated dependencies

## [1.0.12] - 2025-12-01

### Fixed

- post-comments.json datetime incorrect format
- shop page not showing not found error for categories and tags that don't exist

## [1.0.11] - 2025-12-01

### Changed

- updated dependencies

## [1.0.10] - 2025-11-20

### Changed

- updated dependencies

## [1.0.9] - 2025-11-13

### Fixed

- OrderDetails import path case mismatch in checkout OrderReceived

## [1.0.8] - 2025-11-13

### Fixed

- useEmail import path case mismatch in account details Email
- useEmail import path case mismatch in account details Email test
- useEmailForm import path case mismatch in account details EmailForm
- useEmailForm import path case mismatch in account details EmailForm test

## [1.0.7] - 2025-11-13

### Fixed

- Notification import path case mismatch in LoginForm
- Notification import path case mismatch in LostPasswordForm
- Notification import path case mismatch in RegisterForm
- Notification import path case mismatch in ContactForm
- Notification import path case mismatch in NewsletterForm

- Description import path case mismatch in ProductPost Tabs

## [1.0.6] - 2025-11-12

### Fixed

- BlogList import path case mismatch in Blog page
- BlogList import path case mismatch in Home page

## [1.0.5] - 2025-11-12

### Fixed

- PageTitle import path case mismatch in ProductList
- PageTitle import path case mismatch in About page
- PageTitle import path case mismatch in Contact page

## [1.0.4] - 2025-11-12

### Fixed

- Cart import path case mismatch in Cart page

## [1.0.3] - 2025-11-12

### Fixed

- CartObject import path case mismatch in CartReducer
- CartObject import path case mismatch in CartReducer test

## [1.0.2] - 2025-11-12

### Fixed

- CartObject import path case mismatch in CartContext

## [1.0.1] - 2025-11-12

### Fixed

- CartContext import path case mismatch in AppProviders

## [1.0.0] - 2025-11-12

- Initial release
