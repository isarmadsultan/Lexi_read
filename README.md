# Lexi_read
Lexi read App design


# 📱 LexiRead App - UI Screens Description

This document provides a complete overview of each screen in the LexiRead app with required components, input fields, actions, and navigation structure. It is intended for developers to use as a reference for frontend implementation.

---

## 🔶 1. Welcome Screen

**Elements:**
- 📚 **Logo/Icon**: Book with apple illustration (centered)
- 🔘 **Buttons**:
  - `Sign Up` (Primary)
  - `Login` (Secondary)
- 🔗 **Link**:
  - `Forgot your password?` – navigates to password recovery screen

---

## 🔶 2. Create Account Screen

**Elements:**
- 👤 **Profile Picture Placeholder**
  - Tap to upload or take a photo
- 📝 **Input Fields**:
  - First Name
  - Last Name
  - Username
  - Email
  - Password
- ✅ **Checkbox**:
  - "I accept all terms & conditions" (must be checked to enable Sign Up)
- 🔘 **Button**:
  - `Sign Up`

---

## 🔶 3. Login Screen

**Elements:**
- 👤 **User Avatar Icon**
- 📝 **Input Fields**:
  - Email or Username
  - Password
- ✅ **Checkbox**:
  - `Remember me`
- 🔗 **Link**:
  - `Forgot password?` – navigates to reset screen
- 🔘 **Button**:
  - `Login`

---

## 🔶 4. Profile Details Screen

**Elements:**
- 👤 **Profile Picture**:
  - Buttons to `Change photo` or `Remove`
- ✏️ **Editable Fields**:
  - Name
  - Username
  - Email
  - Password
- 🔘 **Bottom Navigation Icons**:
  - Home, Library, Profile

---

## 🔶 5. Home / Dashboard Screen

**Elements:**
- 👋 **Greeting Text**:
  - e.g., `Hi, SARMAD! Welcome back!`
- 🔍 **Search Bar**:
  - For searching books
- 📚 **Recent Readings Section**:
  - Horizontally scrollable list of books
  - Each card includes:
    - Cover Image
    - Title
    - Author
    - Progress (optional)
    - Overflow Menu (three-dot icon)
- 🔘 **Bottom Navigation Icons**:
  - Home, Library, Add Book, Profile

---

## 🔶 6. Book List / Library Screen

**Elements:**
- 🔍 **Search Bar**
- 🔽 **Filter Dropdown**:
  - Example: `By Progress`, `By Title`, etc.
- 📚 **Book List** (vertically scrollable):
  - Cover Image
  - Title
  - Author
  - Progress (if applicable)
  - Overflow menu (options like Edit, Delete, View)

---

## 🔶 7. Add a New Book Screen

**Elements:**
- 📝 **Input Fields**:
  - Title
  - Author
  - Writer of the book (optional or for metadata)
  - Description (optional)
- ⬆️ **Upload Button**:
  - `Upload here` – to add book metadata or content
- 📂 **Top Menu**: Hamburger navigation
- 🔘 **Bottom Navigation**: Home, Library, Add Book, Profile

---

## 🔶 8. Reading Mode / E-Reader Screen

**Elements:**
- 📖 **Book Content View**:
  - Scrollable or paginated text view
- 📌 **Word Selection Popup** (when a word is tapped):
  - Word definition
  - Highlight
  - Add Note
  - Translate
  - Copy
- 🔙 **Top Bar**:
  - Back arrow
  - Book Title

---

## 🔽 Optional Enhancements

To be considered during development:

- Light/Dark mode toggle
- Bookmarking and notes for books
- Reading progress tracking and sync
- Font size and style adjustments
- Offline reading support
- Cloud backup of books and progress

---

## 📌 Bottom Navigation Menu (Visible on Most Screens)

| Icon | Destination |
|------|-------------|
| 🏠 Home | Dashboard screen |
| 📚 Library | All books added |
| ➕ Add | Add a new book |
| 👤 Profile | User account details |

---

