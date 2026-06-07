# ZeroTrace

ZeroTrace is browser extension built around two promises: privacy and quality of life while browsing.

It blocks common tracker and ad requests before they load, then cleans visual clutter so pages feel calmer and easier to use.

## Why ZeroTrace

- Privacy from web trackers and ad systems
- Privacy from unnecessary developer-side visibility
- Cleaner pages with lower visual noise
- Clear controls in popup and full settings page

## Privacy model

ZeroTrace protects from two directions:

- **Web-facing privacy:** blocks many ad and tracker requests, then removes leftover ad clutter.
- **Developer-facing privacy:** protection and preferences stay local in your browser profile, with no account requirement.

Read full policy in [PRIVACY.md](PRIVACY.md).

## Quality-of-life controls

- Master protection switch
- Network blocking
- Cosmetic filtering
- Badge visibility
- Category toggles: ads, trackers, annoyances, social widgets
- Per-site pause and skip controls
- Optional notifications and diagnostics toggles

## Single purpose

ZeroTrace has one purpose: deliver private, low-noise browsing by combining request blocking, page cleanup, and clear user control.

## Permissions

ZeroTrace may use:

- `declarativeNetRequest`
- `storage`
- `scripting`
- `tabs`
- `webRequest`
- `notifications`
- `<all_urls>` host access

Each permission maps to visible user-facing behavior, including protection runtime and per-site controls.

## Support

- Issues: [GitHub Issues](https://github.com/ork89/ZeroTrace-public/issues)
- License: [LICENSE](https://github.com/ork89/ZeroTrace-public/blob/main/LICENSE)
