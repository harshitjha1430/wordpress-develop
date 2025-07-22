 WordPress Core – Custom Fork (Fix for Trac Ticket #63120)

This fork of the [official WordPress Core repository](https://github.com/WordPress/wordpress-develop) contains my contribution to fix a bug related to emoji rendering in plugin titles in the WordPress admin area.

## 🔧 Contribution Summary

- **Issue**: Emoji fallback characters were incorrectly rendered in plugin titles within the admin dashboard.
- **Fix**: Implemented a detection and fallback mechanism to prevent rendering issues for emojis in plugin headers.
- **Ticket Reference**: [Trac Ticket #63120](https://core.trac.wordpress.org/ticket/63120)
- **Pull Request**: [View PR on GitHub](https://github.com/WordPress/wordpress-develop/pull/9293)

## 🧪 Technical Details

- Added logic to check for Unicode rendering issues in plugin headers.
- Ensured backward compatibility with existing plugin title handling.
- Tested changes in local `wp-env` development environment.

## 📂 About This Repository

This repository is a **fork of the official WordPress Core** repository and is used to track and demonstrate the patch I submitted for the bug.

> 💡 For the latest official WordPress source code, please visit [github.com/WordPress/wordpress-develop](https://github.com/WordPress/wordpress-develop)

---

## 🙋‍♂️ Author

**Harshit Jha**  
- GitHub: [@harshitjha1430](https://github.com/harshitjha1430)
  

