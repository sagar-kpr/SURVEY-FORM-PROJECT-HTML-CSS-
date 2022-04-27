<!--THIS IS A SURVEY FORM PROJECT-->
<!DOCTYPE HTML>
<html>
    <head>
        <style>
            body{ background-color: green; text-align:center; font-family:verdana; }
            
            #form {background-color:white; max-width:600px; margin:50px auto; padding:30px 20px; box-shadow: 15px 15px 15px rgba(0,0,0,0.5);}
            .form_control { text-align:left; margin-bottom:20px;}
            .form_control label { display:block; margin-bottom:10px;}
            .form_control input, .form_control select, .form_control textarea { width:95%;
                border:1px solid grey; border-radius: 2px; font-family:Verdana; padding:10px;
            }
            .form_control input[type='radio'], .form_control input[type='checkbox'] { width:auto; display:inline-block;}
            
            button { background-color:lightgreen; font-family:inherit; width:95%; display:block; margin-top:30px; font-size:20px;
                border: 1px solid black; border-radius: 5px; 
            } 
            
                
        </style>
    </head>
    <body>
        <h1>Survey Form</h1>
        <form id="form">
            <!--div-1-->
            <div class="form_control">
                <label for="name" id="label_name" >Name</label>
                <input id="name" type="text" placeholder="Enter Your Name" required>
            </div>
            
            <!--div-2-->
            <div class="form_control">
                <label for="email" id="label_email" >Email</label>
                <input id="email" type="email" placeholder="abc@example.com" required>
            </div>
            
            <!--div-3-->
            <div class="form_control">
                <label for="birth" id="label_birth" >Date Of Birth</label>
                <input id="birth" type="date" required>
            </div>
            
            <!--div-4-->
            <div class="form_control">
                <label for="role" id="label_role">Which Option Describes You</label>
                <select id="role" name="role">
                    <option value="student">Student</option>
                    <option value="professional">Professional</option>
                    <option value="intern">Intern</option>
                </select>
            </div>
            
            <!--div-5-->
            <div class="form_control">
                <label for="checkbox" id="label_checkbox">Languages You Know</label>
                <input id="checkbox"  type="checkbox" name="c" checked>C<br>
                <input id="checkbox"  type="checkbox" name="c++">C++<br>
                <input id="checkbox"  type="checkbox" name="c#">C#<br>
                <input id="checkbox"  type="checkbox" name="java">Java<br>
                <input id="checkbox"  type="checkbox" name="javascript">JavaScript<br>
                <input id="checkbox"  type="checkbox" name="python">Python
            </div>
            
            <!--div-6-->
            <div class="form_control">
                <label for="rate" id="label_rate">Rate My Page</label>
                <input id="rate"  type="radio" name="radio">Below<br>
                <input id="rate"  type="radio" name="radio">Average<br>
                <input id="rate"  type="radio" name="radio" checked>Mind-Blowing
            </div>
            
            <!--div-7-->
            <div class="form_control">
                <label id="label_comment" for="comment">Any comments or suggestions</label>
                <textarea id="comment" name="comment" placeholder="enter your comment here" required></textarea>
            </div>
            
            <button type="submit" value="submit">Submit</button>
            
        </form>
    </body>
</html>
