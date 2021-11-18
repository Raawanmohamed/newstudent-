# newstudent-
<html>
    <head>
        <title>
            student life
        </title>
    </head>
    <body>
        <!--start nav-->
       <a href="index.html"target="_self">Home Page</a>&nbsp;
           <a href="Newstudents.html"target="_self"> New students </a>&nbsp;
           <a href="studentlife.html"target="_self">Student life </a> &nbsp;
        <!--end nav-->
        <!--start section-->
        <form method="post" action="studentlife.html">
            <h1 class="title">new student</h1>
            <fieldset>
                <!--personal info-->
                <legend>personal information</legend>
                <p>
                    <label>
                        full name:
                        <input type="text" name="textfullname">
                    </label>
                    
                </p>
                <p>
                    <label>
                        birthday date:
                        <input type="date" name="textbirthdaydate">
                    </label>
                </p>
                <p>
                    <label>
                        gender:
                        <input type="radio"name="gender" value="male">male
                        <input type="radio"name="gender" value="female">female
                    </label>
                </p>
                <!--#personal info-->
                
            </fieldset>
            <fieldset>
                <!--contact info-->
                <legend>contact info</legend>
                <p>
                    <label>
                        Email:
                        <input type="email" name="textemail">
                    </label>
                </p>
                <p>
                    <label>
                        phone number:
                        <input type="tel" name="textphonenumber">
                    </label>
                </p>
                <p>
                    <label>
                        Address:
                        <textarea row="6"coloums="100" name="textaddress"></textarea>
                    </label>
                </p>
                <!--#contact info-->
            </fieldset>
            <fieldset>
                <!--university info-->
                <legend>
                    university information
                </legend>
                <p>
                    <label>
                        choose your faculty:
                        <select name="faculty">
                            <option value="f1">computer science</option>
                            <option value="f2">engineering</option>
                            <option value="f3">political science</option>
                        </select>
                        

                    </label>
                </p>
                <!--#unversity info-->
            </fieldset>
            <input type="submit" class="button" value="Add" name="Add">
        </form>


        <!--end section-->
        <!--start footer-->
        <a href="www.fue.edu.eg"target="_blank">&copy;future university in egypt</a>&nbsp;
        <a href="mailto:20203158@fue.edu.eg"target="_blank">contact us</a>
          <!--end footer-->
    </body>
</html>
