Mocks for [google_sign_in](https://pub.dev/packages/google_sign_in). Use this
package with `firebase_auth_mocks` to write unit tests involving Firebase
Authentication.

## Usage

A simple usage example:

```dart
import 'package:google_sign_in_mocks/google_sign_in_mocks.dart';

main() {
    final googleSignIn = MockGoogleSignIn();
    final signinAccount = await googleSignIn.signIn();
    final signinAuthentication = await signinAccount.authentication;
}
```

## Features and bugs

Please file feature requests and bugs at the issue tracker.
