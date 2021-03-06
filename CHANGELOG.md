# Change Log

## [0.5.0] - 2016-05-26
### Added
- Welcome messages.
- You may now verify that the message is from Facebook by
  configuring `app_secret`.
- Support for Rack 2.
- Support for receiving attachments from the user.

## [0.4.2] - 2016-05-02
### Fixed
- Fix a bug that caused `Subscriptions.subscribe` and
  `Subscriptions.unsubscribe` to not raise errors.

## [0.4.1] - 2016-05-02
### Fixed
- Fix a bug that caused `Bot.deliver` to return `'message_id'` for successful
  deliveries and `nil` for unsuccessful deliveries instead of a message ID or
  appropriate exceptions.

## [0.4.0] - 2016-04-29
### Added
- Support for threaded servers.

### Fixed
- Fix a bug that caused a `NoMethodError` with no hooks at all.

## [0.3.0] - 2016-04-24
### Added
- Add support for optins.

### Fixed
- Fix a bug that prevented registering postbacks.

## [0.2.0] - 2016-04-23
### Added
- Everything!

## [0.1.0] - 2016-04-15
### Added
- Nothing; release an empty codebase to snag the name.
