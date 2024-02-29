# Password Manager

In this project, let's build a **Password Manager** 

![Password Manager](https://assets.ccbp.in/frontend/content/react-js/passowrd-manager-output-v0.gif)

## Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-sm-output-v2.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Masked Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-masked-passwords-sm-output-v2.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Show Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-sm-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Masked Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-masked-passwords-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Show Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-lg-output.png)

</details>

## Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

## Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities:

- Initially, the website input, username input, and password input should be empty and [No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png) should be displayed.
- When non-empty values are provided for the website, username, and password and the **Add** button is clicked:
  - A new password item should be added to the list of passwords.
  - The passwords count should be incremented by one.
  - The **stars image** should be displayed in the password items instead of the passwords.
  - The value of the input fields for website, username, and password should be updated to their initial values.
  - When the **Show Password** is checked, then the password should be displayed instead of the **stars image**.
- When a non-empty value is provided in the search input field, then password items whose website is matched with the search input value irrespective of the case should be displayed.
- When a non-empty value is provided in the search input field, and if the website of any password item does not match the value given in the search input, then [No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png) should be displayed.
- When the delete button of a password item is clicked:
  - The respective password item should be deleted from the list of passwords.
  - The passwords count should be decremented by one.
- When all password items are deleted, then [No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png) should be displayed.
</details>

## Important Note

<details>
<summary>Click to view</summary>

**The following instructions are required for the tests to pass**:

- HTML input element for website should have the placeholder as **Enter Website**.
- HTML input element for username should have the placeholder as **Enter Username**.
- HTML input element for password should have the placeholder as **Enter Password**.
- The delete button for each password item should have the testid as **delete**.
</details>

## Resources

<details>
<summary>Image URLs</summary>

- ![app logo](https://assets.ccbp.in/frontend/react-js/password-manager-logo-img.png)
- ![password manager](https://assets.ccbp.in/frontend/react-js/password-manager-sm-img.png)
- ![password manager](https://assets.ccbp.in/frontend/react-js/password-manager-lg-img.png)
- ![website](https://assets.ccbp.in/frontend/react-js/password-manager-website-img.png)
- ![username](https://assets.ccbp.in/frontend/react-js/password-manager-username-img.png)
- ![password](https://assets.ccbp.in/frontend/react-js/password-manager-password-img.png)
- ![search](https://assets.ccbp.in/frontend/react-js/password-manager-search-img.png)
- ![no passwords](https://assets.ccbp.in/frontend/react-js/no-passwords-img.png)
- ![stars](https://assets.ccbp.in/frontend/react-js/password-manager-stars-img.png)
- ![delete](https://assets.ccbp.in/frontend/react-js/password-manager-delete-img.png)
</details>

<details>
<summary>Colors</summary>

- #9ba9eb
- #c3caea
- #5763a5
- #f8fafc
- #454f84
- #0b69ff
- #94a3b8
- #b6c3ca
- #7683cb
- #f59e0b
- #10b981
- #f97316
- #14b8a6
- #b91c1c
- #ffffff
- #0ea5e9
- #64748b
</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
