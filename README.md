# mnist_digit_mobile

This is a placeholder app to rapidly test the accuracy of your handwritten digit classifier app with your own hands!!!
Yes, you heard it right. You can install the apk file of this repository in your android app, and test the effectiveness of your classifier.
The iOS version will be released soon.

## Handwritten Digit Classifier Sample Predictions for the android version

Here are some sample predictions from the Handwritten Digit Classifier app:

<img src = 'https://github.com/SriramBharadwaj1/mnist_digit_mobile/blob/master/assets/sample_predictions.jpeg' height = 500>

The image above shows the output of the classifier when tested with some handwritten digits.


## Prerequisites

- Git
- Android Studio

## Instructions

1. **Clone the Repository**

    Open a terminal and run the following git command:

    ```bash
    git clone https://github.com/SriramBharadwaj1/mnist_digit_mobile.git
    ```

2. **Open the Project in Android Studio**

    - Start Android Studio.
    - From the Android Studio menu select `File > Open`.
    - Navigate to the directory where you cloned the project.
    - Select the `mnist_digit_mobile` directory and click `OK`.
    - Android Studio loads the project and you are ready to explore!
3. **Adding your custom classifier in Android Studio**
    - Open **Android Studio** on your computer.
    - Click on `File > Open...` from the menu bar.
    - Navigate to the location where you have saved the project and click `OK`.
    - Android Studio will take a few moments to import the project and set up the environment.
    - Once the project is loaded, click on `Build > Build Bundle(s) / APK(s) > Build APK(s)`.
    - After the build is complete, you will see a notification at the bottom of the screen saying `APK(s) generated successfully`.
    - Click on `locate` in this notification to navigate to the generated APK file.
    - You can now deploy this APK file to any Android device for testing.

Please ensure that you have replaced the `.tflite` file as per previous instructions before building the APK.

# Contribution Guidelines

I welcome and appreciate all contributions to the MNIST Digit Mobile project! Any kind of improvements to the UI or additional functionality, or even to the README.MD file are welcome Here's how you can contribute:

## Prerequisites

- Basic knowledge of Git and GitHub.
- Android Studio installed on your machine.

## Steps to Contribute

1. **Fork the Repository**

    Start by forking the MNIST Digit Mobile repository.

2. **Clone the Forked Repository**

    Clone your forked repository to your local machine. Go to your GitHub account, open the forked repository, click on the `Code` button and then click the `copy to clipboard` icon.

    Open a terminal and run the following git command:

    ```bash
    git clone "url you just copied"
    ```

3. **Create a New Branch**

    Change to the repository directory on your computer (if you are not already there):

    ```bash
    cd mnist_digit_mobile
    ```

    Now create a branch using the `git checkout` command:

    ```bash
    git checkout -b your-new-branch-name
    ```

4. **Make Necessary Changes and Commit Those Changes**

    Now you can go ahead and make changes to the files.

    Once you've made changes or added files, it's time to commit. You can use the following commands:

    ```bash
    git add .
    git commit -m "commit message"
    ```

5. **Push Changes to GitHub**

    Push your changes using the command `git push`:

    ```bash
    git push origin <add-your-branch-name>
    ```

6. **Submit Your Changes for Review**

    If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

7. **Create a Pull Request**

    Now submit the pull request, providing detailed explanations of what you did.

Once you've submitted a pull request, we'll review your changes and merge them if they're helpful!

## Opening Issues

If you encounter any problems or have suggestions for improvements, please open an issue. Here's how:

1. Go to the Issues tab in the MNIST Digit Mobile repository.
2. Click on `New issue`.
3. Write a descriptive title in this format: 'Issue #num : <the issue>'. The 'num' should correspond to the next issue number.
4. Describe your issue or suggestion in detail.
5. Click on `Submit new issue`.

Thank you for your contributions!
