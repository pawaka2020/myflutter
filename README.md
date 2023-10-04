# myflutter

Suggested screens with navigation tree (WIP):
- SplashScreen
  |
  +-- OnboardingScreen
  |
  +-- AuthenticationFlow
  |   |
  |   +-- LoginScreen
  |   |
  |   +-- RegistrationScreen
  |
  +-- MainAppFlow (Authenticated User)
  |   |
  |   +-- HomeScreen
  |   |
  |   +-- MenuScreen
  |   |
  |   +-- ProductDetailScreen
  |   |
  |   +-- CartFlow
  |   |   |
  |   |   +-- CartScreen
  |   |   |
  |   |   +-- CheckoutScreen
  |   |   |
  |   |   +-- OrderHistoryScreen
  |
  |   +-- ProfileFlow
  |   |   |
  |   |   +-- ProfileScreen
  |   |   |
  |   |   +-- FavoritesScreen
  |
  |   +-- StoreLocatorScreen
  |
  |   +-- NotificationsScreen
  |
  |   +-- SettingsScreen
  |   |   |
  |   |   +-- ContactScreen
  |   |   |
  |   |   +-- RateAndReviewScreen
  |
  |   +-- LogoutScreen
  |
  +-- PromotionsScreen
  |
  +-- FeedbackScreen
  |
  +-- AboutScreen


Suggested app structure (WIP):
- lib
  |
  +-- main.dart (entry point)
  |
  +-- screens
  |   |
  |   +-- splash_screen.dart
  |   |
  |   +-- onboarding_screen.dart
  |   |
  |   +-- authentication
  |   |   |
  |   |   +-- login_screen.dart
  |   |   |
  |   |   +-- registration_screen.dart
  |   |
  |   +-- main_app_flow
  |   |   |
  |   |   +-- home_screen.dart
  |   |   |
  |   |   +-- menu_screen.dart
  |   |   |
  |   |   +-- product_detail_screen.dart
  |   |   |
  |   |   +-- cart_flow
  |   |   |   |
  |   |   |   +-- cart_screen.dart
  |   |   |   |
  |   |   |   +-- checkout_screen.dart
  |   |   |   |
  |   |   |   +-- order_history_screen.dart
  |   |
  |   |   +-- profile_flow
  |   |   |   |
  |   |   |   +-- profile_screen.dart
  |   |   |   |
  |   |   |   +-- favorites_screen.dart
  |   |
  |   |   +-- store_locator_screen.dart
  |   |   |
  |   |   +-- notifications_screen.dart
  |   |   |
  |   |   +-- settings_screen.dart
  |   |   |   |
  |   |   |   +-- contact_screen.dart
  |   |   |   |
  |   |   |   +-- rate_and_review_screen.dart
  |   |   |
  |   |   +-- logout_screen.dart
  |   |
  |   +-- promotions_screen.dart
  |   |
  |   +-- feedback_screen.dart
  |   |
  |   +-- about_screen.dart
  |
  +-- widgets
  |   |
  |   +-- custom_button.dart
  |   |
  |   +-- custom_app_bar.dart
  |   |
  |   +-- ...
  |
  +-- models
  |   |
  |   +-- user.dart
  |   |
  |   +-- product.dart
  |   |
  |   +-- order.dart
  |
  +-- services
  |
  +-- authentication_service.dart
  |
  +-- cart_service.dart
  |
  +-- user_service.dart
  |
  +-- ...

