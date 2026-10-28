HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
</head>
<body>

    <main>
        <h1>Student Registration Form</h1>

        <form action="#" method="POST">
            <!-- Full Name -->
            <div>
                <label for="full-name">Full Name:</label>
                <input type="text" id="full-name" name="fullName" required placeholder="John Doe">
            </div>
            <br>

            <!-- Email -->
            <div>
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required placeholder="student@example.com">
            </div>
            <br>

            <!-- Password -->
            <div>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <br>

            <!-- Phone Number -->
            <div>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required placeholder="123-456-7890">
            </div>
            <br>

            <!-- Age -->
            <div>
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" min="16" max="100" required placeholder="18">
            </div>
            <br>

            <!-- Submit Button -->
            <div>
                <button type="submit">Submit Registration</button>
            </div>
        </form>
    </main>

</body>
</html>
Key Requirements Checklist Covered
Form Structure: Wrapped inside a primary <form> tag.

Labels: Each <input> element is explicitly paired with a matching <label> via for and id attributes.

Input Types: Includes type="text", type="email", type="password", type="tel", and type="number".

Attributes: Unique id, descriptive name, and the required validation attribute applied to mandatory fields.

Submission: Includes a functional submit button to complete the form.