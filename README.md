# Assignment #4: Forms and Validation

Student: Zhakanov Sanzhar
Group: SE-2526

A simple website made with HTML, CSS, and Bootstrap.
No JavaScript is used.

## Pages

- index.html — Task 0: basic contact form.
- task1.html — Task 1: HTML5 validation.
- task2.html — Task 2: Bootstrap contact form and grid.
- task3.html — Task 3: Bootstrap validation styles and feedback.
- task4.html — Task 4: responsive registration form.

## Run

Place all files in the same folder and open index.html in a browser.
Use the navigation bar to switch between tasks.

An internet connection is needed to load Bootstrap.

## Validation

HTML5 attributes check required fields, email format, and text length.

Task 3 includes fixed examples of is-valid and is-invalid.

The forms in Tasks 3 and 4 use Bootstrap's was-validated class.
Bootstrap CSS displays feedback based on the browser's validation.
Feedback is visible from the start and updates when fields change.

Both password fields require at least 8 characters.
Password matching is not checked.

## Form submission

These forms demonstrate frontend validation only.
Submitting a valid form reloads the current page with named fields
in the URL. There is no server that processes or stores submissions.

Password fields have no name attribute and are excluded from the URL.
No account is created.

## Testing

1. Submit empty required fields.
2. Enter an invalid email address.
3. Enter a short message in Tasks 1 and 3.
4. In Tasks 3 and 4, correct invalid fields and observe the feedback.
5. In Task 4, enter fewer than 8 characters in a password field.
6. Leave gender or country empty and submit.
7. Complete all required fields and submit.
8. Click Reset to restore the registration form's initial state.
9. Resize the browser to check the responsive layout.

## Publish using GitHub Pages

1. Create a GitHub repository.
2. Upload all project files to the repository root.
3. Open Settings → Pages.
4. Select Deploy from a branch.
5. Select main and / (root), then save.
6. After deployment, copy the published website URL.

Repository URL: Add your repository link here.
Published website URL: Add your GitHub Pages link here.