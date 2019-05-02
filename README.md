# S-W-testing-Project
Minimal ToDo is an android app where you can track your daily todos. With this app, you can create your own todo list and manage by setting date and time. Alogn with date and time, you can set reminder and snooze options for created todos.

# 2.1. Location of unit tests 
The local unit tests of an Android project are located in the app/src/test folder.

# 2.2. Required dependencies in the Gradle build file
  To use JUnit tests for your Android application, you need to add it as dependency to your Gradle build file.

    dependencies {
      // Unit testing dependencies
      testCompile 'junit:junit:4.12'
      // Set this dependency if you want to use the Hamcrest matcher library
      testCompile 'org.hamcrest:hamcrest-library:1.3'
      // more stuff, e.g., Mockito
    }


# 2.3. Running the unit tests
   ## 2.3.1. Using Gradle
      Run your unit tests with the gradlew test command.
   ## 2.3.2. Using Android Studio
      To run a unit test, right-click on your test class in the Project window and select Run.

# 2.4. Location of test reports
The Test reports are created in the app/build/reports/tests/debug/ directory. The index.html gives an overview and links to the individual test pages.



