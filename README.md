# INTERNATIONAL RESEARCH AND INVENTION EXHIBITION IRIE 2020 MOBILE APP 

Name | Matric Number
------------ | -------------
Hanan Allil | 1617888
Mais Alhamidi | 1632714
Zubaidah Mohammed Alwan | 1623496
Nurul Aqilah Binti Abdul Ghaffar | 1620090

Instructor’s Name - Dr. MUHAMAD SADRY ABU SEMAN


**INTRODUCTION**

In 2020, we are living in a new normal because of COVID19 pandemic. This new normal includes registering our details such as full name, mobile number and location before we enter any business premise. Thus, we want to build an app called International Research and Invention Exhibition IRIE 2020 with the aim to ease the registration process of the exhibition for both the exhibitors and visitors. With this app, the admin can process beforehand the details of the participants to ensure a smooth process during the exhibition as every organizer needs to abide by the standard operating procedure of the COVID19, which there is limitation to the number of people gathered for an exhibition.  The admin can also organize the exhibition more systematically with the details that they obtained from this app. Moreover, this app will consist of many functionalities such as authentication, registration, feedback and will be developed using react native language and firebase as the back-end.

**OBJECTIVES**
1. To ease the registration process of the exhibition for the exhibitors and visitors.
1. To help the admin organize the exhibition by obtaining participants data before the exhibitions.

**FEATURES AND FUNCTIONALITIES**

As our proposed mobile application is “INTERNATIONAL RESEARCH AND INVENTION EXHIBITION IRIE 2020”. We decided as a group to encounter a number of features and functionalities that are suitable for this type of mobile application. 

**Features:**
1. Flexibility: our mobile app is very flexible and simple to use apparently by two basic users such exhibitors and visitors. Moreover, the exhibitors can register by simply entering their credentials by the specified form. Thus, for exhibitors it will be an easy endeavor to reserve online the suitable slot and make sure easily they can present their poster at that exhibition. However, there is another type of form for visitors that enables them to do online registration. Consequently, it is comfortable for any visitors from different areas to save their time especially if they are coming from far away by just assuring the registration online. Lastly, it will be solving the problem of costly, complicated, inconvenient manual registration.
1. Security feature: We aim to secure our users and enable unique security that is advantageous in our mobile app. As the security can be implemented in different types through multiple ways. However, in our mobile app we enable authentication as our security method at first point by requesting from users to authenticate him/herself. So, we can make sure that who are our users either if they are visitors or exhibitors that use our mobile application to register. Additionally, if a user already registered or exists in the database, so can simply log in to authenticate who is by entering credentials. While, new users should sign up by entering their details also .
1. Feedback feature: Although, the way we allow applicants to register online but, it is an important factor to furnish them with feedback regularly. Since then, we have goals to provide them with feedback to keep awareness with our users such as confirming for them the process of registration. Although, our mobile app can ease the way for them to do registration online but without assuring the status of registration so it will be religious. So, we will furnish the applicant or participant with feedback that confirmed for them the registration if it is done or not. To illustrate, the exhibitor in this way can make sure they successfully done registration or not, so they are able to recognize or manage better preparation for posters at specified time while if not successfully register can also manage to find replacement.
 

**Functionality:**

**API**
Besides the various API that are available and can be integrated into such any type of mobile app we decided to include API  QR code and Scanner. The reason why we choose API QR code is that it is most suitable for our mobile app project type specifically to generate the QR code after the exhibitor doing the register form. To generate  the poster abstract for exhibitors and make sure their registration is saved by the QR code. In addition, the Scanner goal is also for the visitor to scan the Qr code and take them to the poster abstract  and show them the poster details.
 The QR code and Scanner, will benefit the Exhibitor and the Visitor as the  users, so here we decide to have a QR code generator which aims to generate the Qr Code for the poster abstract that is entered by the user. So, by this, it can benefit the user either visitor or exhibitor when the QRcode is generated. .As well as In our app we had created a scanner that allows the visitor to scan the QR code which helps to show the poster list detail via scanning the Qr code. Moreover, the visitor can show the available poster list easily through scanning the Qr code which can be on the list at the beginning when the visitor wants to register in these exhibitions.Otherwise, if visitors scan any Qr code which is not related to the poster. Basically, the scanner serves as a basis for any visitor to check the available list of posters easily.So based on your request we have included the Qr code generator and scanner as our API.


**Components**
As it is stated that react native component  is a basic part in developing any type of mobile app.Also, it is divided in two main parts such container and presentational component.Hence, in our project the basic to include container such for states,props and function for make it work eventually.Here the container role as this application will ease the way for users and exhibition visitors by allowing them to register online and include their personal information , the users can be the participants who are in favour to show their poster on that day. Thus, the application will make the ability to provide an opportunity for researchers to interact and exchange ideas and also to promote international collaborative research and give the opportunity to exhibit research outputs at global level.Furthermore, where visitors will be able to register online,our application will solve common problem that most visitors are far away from the university location and can not register on exhibition time and that not acceptable if lead them to miss that day. However, for the appearance and styling of our mobile app we can include such any type of presentational component like UI toolkit or nativebase.To be clear, for enhancement of our project we will include these components to enable our functionality and objective is working as is planned.

Component details :
 1.Navigation
 In our app we have more than one screen that we  navigate , the navigation  it will  help us to navigate between the screen in the app  includes  in the Appstack to navigate the multiple screen, the Authstack is to access data associated with a user or other private content.
1.IconButton: An icon button is a button that displays an icon such as icon name, color, size , onpress , style .
1.Button: Allow the user to navigate to another screen using the button clicking.For example, view poster button allows the user to navigate to poster detail when clicking it.Button component for handling touches that should render nicely on the app
1.Spinner: This component enhances a text input for entering numeric values, with an increase and decrease buttons.
1.ScrollView: It helps to choose from the menu by scrolling over the screen.For example, when the user scrolls over the poster type, here can choose the preferred one by scrolling over.
1.Style: The most important thing in the mobile app is styling,It makes our application attractive here we use inline style.
1.View:  it helps in building the app UI.The view includes the component where it should be rendered then to be represented.For example, style, button and other components should be included here.
1.Card: This component adds a box-shadow by default.Also provides default spacing and alignment between cards.
1.CardItemThis is the child component of card.Works very similar to the list items of list.Takes input such as: Text, Button, Image, Thumbnail, Icon.Card takes any number of CardItem.
1.Navigators: it helps us to change the scene in the app, in our app we have more than one screen we navigate the user to multiple scenes. We do this by using navigators.
1.Alert: it is an alert dialog with the specified title and message such as when the user after doing the exhibitor form it will give a message that the poster added successfully or if the user is missing to do input in the form also it will give the alert message that he is missing something when doing the register form.
1.TexInput: A component for inputting text into the app by getting a text from the user by keyboards like the title of the project and other stuff.
1.Render : where the  content inside the render will  be displayed in the Application screen.


**Error checking:**
The error checking is an important function in determining the registration process if it can be continued successfully or not. Errors occur when people engage with user interfaces. Sometimes, they happen because users make mistakes. Sometimes, they happen because an app fails. Subsequently, in our project we will enable error checking that check for logic errors and unexpected app errors. For example, it will result in user error if the details entered at the wrong place, field required not filled and other logic mistakes. Error checking can assure the authentication correctly by intended users because if requested details are not entered correctly hence it will return error. By this way, we will handle logic errors that are encountered by users or on the app so our mobile app can be executed as intended.

For authentication, we use Formik and Yup libraries to help handle error checking. By using Formik, it can handle server errors and handle different field types in forms. We use Yup’s validation schema where it consists of error checking such as it will return an error if the user wrongly input unregistered email or input password that has less than 6 characters. Furthermore, in the registration screen, Yup will check the length of the string whether it is too short or long for variable name and password. For an accurate registration process, a confirm password field is also required to ensure the user rightly registered the password. Moreover, for privacy purposes, a function to handle the password visibility is made to ensure the password entered by the user is hidden. For exhibitors and visitors form, the required fields such as ‘Name’ and ‘Author name’ need to be filled or else an alert will pop out to ask the user to fill the field.



**Authentication**
Basically, any platform that is designated to serve users should be entertained with security features, so the security issue is not violated. However, we decided to include one of the significant security requirements which is user authentication. Based on that, we will encounter two forms of authentication that allow exhibitors and visitors to be able do pre-registration. Also, it will authenticate users based on user situations such as new users or not. The new user needs to sign up first then proceed to do the registration online while if already the user name listed in the firebase data storage will need only to log in. As a result, we can authenticate those who are our users by enabling authentication forms that check according to data storage at firebase to enable authenticate users by matching if existing or recognizing a new user.For authentication at our app is so powerful as we include the login and registration button to authenticate the user for security purpose.Hence,the login button will allow the user to login to the app by just the registered email and password.While,for first time the user must registered by credential entering such name,password and email.

 
**Firebase for data storage:**
 Using firebase will serve  as a database system that registers details of our users such as     applicants or visitors. So, it will store the details of users which can be useful later in the authentication and registration process. Based on that, the role of firebase to check that if the registration slots are  full or not based on database storage.Since then, the user is permitted to register through the form if there is place and then it will be listed that registered successfully.While if it is full,it will appear for the user that it is full and can not be added.Lastly, we can said that the firebase role is so useful as will help us as the data storage which result in enabling registration based on the existent places.So, when developing the app, we have stored and retrieved any data entered by the user,visitor and exhibitor at firebase in the database section.Based on that, it can said that the firebase serves as storage for our exhibition data mobile app.


**SCREEN NAVIGATION**

The figure below shows the screen navigation design for IRIE system:
 
 ![Screen Navigation](/screen.png)


                                                Figure (1) Screen Navigation Diagram 

**SEQUENCE DIAGRAM**

 This is a sequence diagram to represent the interaction of the proposed mobile application.
 
 ![Sequence Diagram](/sequence.png)


                                                Figure (2) Sequence Diagram 

  

**REFERENCES**

https://online.visual-paradigm.com/drive/#diagramlist:proj=0&new=MobileWireflow
https://www.npmjs.com/package/react-native-push-notification
https://reactnative.dev/docs/components-and-apis
https://docs.nativebase.io/Components.html#button-icon-headref
https://docs.expo.io/versions/latest/sdk/permissions/
https://reactnavigation.org/docs/stack-navigator/
https://docs.expo.io/versions/latest/sdk/bar-code-scanner/







