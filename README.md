# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page:Bureau of Police Research And Development</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sansita&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

</head>

<body style="font-family: 'Sansita', sans-serif;">
    <div class="container-fluid bg-light text-black text-center" style="width:1440px;height:200px;">
        <img src="./img/header.JPG" class="img-fluid" style="width:100%; height:200px;" alt="BPR&D">
    </div>
    <div class="container-fluid" style="background-color: #641F85;width:1410px;height: 60px; padding-top: 10px;">
        <div class="col" style="padding-left: 1175px;">
            <a class="rounded-circle float-start " href="https://twitter.com/bprdindia?lang=en" target="_blank">
                <img src="./img/logotwt.png" style="width:50px;height:50px;margin-top: -5px;" alt="Twitter">
            </a>
            <a class="rounded-circle float-start" href="https://www.facebook.com/officialBPRDIndia" target="_blank">
                <img src="./img/logofb.png" style="width:50px;height: 50px;margin-top: -5px;" alt="Facebook">
            </a>
            <a class="rounded-circle float-start" href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow" target="_blank">
                <img src="./img/logoyt.png" style="width:50px;height: 50px; margin-top: -5px;" alt="Youtube">
            </a>
            <a class="rounded-circle float-start" href="https://www.instagram.com/bprdindia/" target="_blank">
                <img src="./img/logoinsta.png" style="width:50px;height:50px;margin-top: -5px;" alt="Instagram">
            </a>
        </div>
        <div class="dropdown" style="top: -44px;">
            <button class="btn  dropdown-toggle" type="button" data-toggle="dropdown" style="background-color: #0C0D45; color: white;padding-right: 10px;height: 40px;padding-bottom: 5px;font-size: larger; ">MENU
            </button>
            <ul class="dropdown-menu" style="color: aliceblue; font-size: 20px; background-color: #641F85;">
                <div class="container-md" style="background-color: #641f85;">
                    <div class="row" style="background-color: #641f85;">
                        <div class="col-sm" style="background-color: #641f85;">
                            <li style="color: #4690ff;">HOME</li>
                            <li style="color: #8685d0;">ABOUT US</li>
                            <li>Evolution</li>
                            <li>Awars/Medals</li>
                            <li>Work Allocation</li>
                            <li>Contact Us</li>
                        </div>
                        <div class="col-sm" style="background-color: #641f85;">
                            <li>GALLERY</li>
                            <li style="color: #8685d0;">RESEARCH & CA</li>
                            <li>Research</li>
                            <li>Correctional admin</li>
                            <li>Interns Talk</li>
                            <li>SC Questionnaire</li>
                        </div>
                        <div class="col-sm" style="background-color: #641f85;">
                            <li>PUBLICATION/REPORTS</li>
                            <li style="color: #8685d0;">SPD</li>
                            <li>Data on police organization</li>
                            <li>police book of BPRandD</li>
                            <li>Indian police journal</li>

                        </div>
                        <div class="col-sm" style="background-color: #641f85;">
                            <li>DOPO</li>
                            <li style="color: #8685d0;">TRAINING</li>
                            <li>Dmoestic courses</li>
                            <li>Foreign courses</li>
                            <li>Training calender</li>
                            <li>Training policy</li>
                        </div>
                    </div>

                    <div class="row" style="background-color: #641f85">
                        <div class="col-sm" style="background-color: #641f85;">
                            <li style="color: #8685d0;">SPC</li>
                            <li>Student police cadet</li>
                            <li>Conference</li>
                            <li>Police Expo 2020</li>
                        </div>

                        <div class="col-sm" style="background-color: #641f85;">
                            <li style="color: #8685d0;">MODERNIZATION</li>
                            <li>History</li>
                            <li>Ongoing projects</li>
                            <li>Mandate of modernization</li>
                            <li>publication/reports</li>
                        </div>
                        <div class="col-sm" style="background-color: #641f85;">
                            <li style="color: #8685d0;">ADMIN</li>
                            <li>Administration division</li>
                            <li>Recruitment rules</li>
                            <li>Ongoing projects</li>
                            <li>Recruitments</li>
                        </div>
                        <div class="col-sm" style="background-color: #641f85;">
                            <li style="color: #8685d0;">NPM</li>
                            <li>Genesis</li>
                            <li>Concept and objectives</li>
                            <li>Structure</li>
                            <li>status of projects</li>
                        </div>

                    </div>
                </div>
            </ul>
        </div>

    </div>
    <div class="container" style="height: 15px;">
    </div>
    <div class="container-fluid" style="background-color:#E6D2FA; width: 1410px; height: 500px;">
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            <!-- Indicators -->

            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active" style="background-color: #5A60FF;"></li>
                <li data-target="#myCarousel" data-slide-to="1" style="background-color: #5A60FF;"></li>
                <li data-target="#myCarousel" data-slide-to="2" style="background-color: #5A60FF;"></li>
                <li data-target="#myCarousel" data-slide-to="3" style="background-color: #5A60FF;"></li>
            </ol>

            <!-- Wrapper for slides -->
            <div class="carousel-inner" style="padding-left: 63px; margin-top: 23px;">
                <div class="item active">
                    <img src="./img/imgslid1.JPG" style="width:1250px;height: 438px;">
                </div>

                <div class="item">
                    <img src="./img/imgslid2.JPG" style="width:1250px;height: 438px;">
                </div>

                <div class="item">
                    <img src="./img/imgslid3.JPG" style="width:1250px;height: 438px;">
                </div>

                <div class="item">
                    <img src="./img/imgslid4.JPG" style="width:1250px;height: 438px;">
                </div>


            </div>
            <a class="left carousel-control" style="padding-top: 195px;padding-right: 140px;" href="#myCarousel" data-slide="prev">
                <div class="leftbt float-start"><span><img src="./img/leftbt.svg" alt="lbt"></span>
                    <span class="sr-only">Previous</span>
                </div>
            </a>
            <a class="right carousel-control" style="padding-top: 205px;padding-left: 135px;" href="#myCarousel" data-slide="next">
                <div class="rigtbt float-end"><span><img src="./img/rightbt.svg" alt="rt"></span>
                    <span class="sr-only">Next</span>
                </div>
            </a>
        </div>

    </div>
    <div class="container-fluid" style="background-color:white;height: 15px;width: 1410px;">
    </div>
    <div class="container-fluid" style="background-color: #641F85;width: 1410px;">
        <div class="row" style="background-color: white;width: 1410px;height:702px;">
            <div class="col-sm-9" style="background-color: #E6D2FA;">
                <img src="./img/whne.svg" alt="wt" height=""><a style="font-size: xxx-large;font-weight: 200;">What's New</a>
                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Invitation of application for the paid Internship Programme at MPR^&D For the year 2022-23  </a>
                <br>
                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Rules for National Level Competition for BPRD's Website Design</a>
                <br>
                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Bureau Darpan</a>
                <br>
                <br>
                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Proceedings of the Webinar on Woman Safety with Sensitivity </a>
                <br>

                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Pandit Govind vallab pant Puraskar Yojana </a>
                <br>
                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Terms and Conditions for engagement of 02 Individual Consultants on Contractual Basis. </a>
                <br>
                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">WOMEN’S SECURITY- A Handbook for First Responders and Investigators in the Police</a>
                <br>
                <br>

                <img src="./img/star.svg" alt="st" style="padding-left: 28px;"><a style="font-size: 25.65px;padding-left: 10px;">Investigative Workflow Manual on Cyber Harassment Cases</a>
            </div>
            <div class="col-sm">
                <img src="./img/balagi.png" width="337.5px" height="389px" style="text-align: left;background-color: #E6D2FA;" alt="">
                <br>
                <div class="container-fluid" style="height: 315px;background-color: #CBA1F4;">
                    <h2 style="font-weight: 200;">BALAJI SRIVASTAVA,IPS,<br>Director General,<br>BPR&D</h2>
                    <h2 style="font-weight: bold;">
                        "Good Policing cannot be <br> perceived without the <br> BPR&D"</h2>
                    </h2>
                    <div style="display: inline;">
                        <img src="./img/vec.svg" alt="vec" width="29px" height="29px"><b><a style="font-size: large;padding-left: 5px;color: #5A60FF;">Read the Message from Director Here</a></b>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container-fluid" style="height: 15px;background-color:white;width: 1410px;">

    </div>
    <div class="container-fluid" style="height: 434px;width: 1410px;background-color: white;">

        <div class="col-md-4" style="background-color:#E8D6FA;height: 450px;box-sizing: border-box;
        border: 5px solid transparent;
        background-clip:padding-box;">
            <h1 style="text-align: center;">News&Events</h1>
            <img src="./img/upar.svg" alt="s" style="padding-top: 16px;float: left;"><b style="font-size: 23px;">Invitation of application for the paid <br> Internship Programme at BPR&D <br> for the year 2022-23-<a style="color: #2E3092; ">17/01/2022</a></b><br><br>
            <img src="./img/upar.svg" alt="s" style="padding-top: 16px;float: left;"><b style="font-size: 23px;">Rules for National Level Competition <br> for BPRD'S Website Design - <br><a style="color: #2E3092; ">18/01/2022</a></b><br><br>
            <img src="./img/upar.svg" alt="s" style="padding-bottom: 50px;float: left;"><b style="font-size: 23px;padding-top: 25px;">Bureau Darpan -<a style="color: #2E3092; ">05/01/2022</a></b><br>

        </div>
        <div class="col-md-4 " style="background-color: #E8D6FA;height: 450px;box-sizing: border-box; border: 5px solid transparent; background-clip:padding-box; ">
            <h1 style="text-align: center; ">Gallery</h1>
            <br>
            <img src="./img/gal1.png " alt="ga " style="float: left; ">
            <ul style="padding-left: 215px;font-size:20px;font-weight: 300; ">
                <b><li>Sabkasanth Sabka vikas</li></b>
                <b><li>51st Foundation Day</li></b>
                <b><li>National Conference of Head of Prisons</li></b>
            </ul>
            <b><a style="padding-left: 110px;font-size: 20px;color: #2E3092; ">Pictures Here</a></b>
            <br> <br><br>
            <ul style="font-size: 20px;float: left;font-weight: 300; ">
                <b><li>Police Expo 2019</li></b>
                <b><li>SPC Theme Song</li></b>
                <b><a style="padding-left: 45px;color: #2E3092; ">Videos Here</a></b>
            </ul>
            <img src="./img/gal2.png " alt="2 " style="padding-left: 62px; ">

        </div>
        <div class="col-md-4 " style="background-color:#E8D6FA;height: 450px;box-sizing: border-box; border: 5px solid transparent; background-clip:padding-box; ">
            <div style="display: inline-block;background-color: #E8D6FA;width: 430px; ">
                <h1 style="text-align: center;display: inline-block;background-color: #E8D6FA; ">Press Release</h1>
                <h1 style="text-align: center;display: inline-block;margin-left: 30px;background-color: #641F85;width:199.1px ;height: 60px; ">Tenders</h1><br><br>
                <img src="./img/upar.svg" alt="s" style="padding-bottom: 50px;float: left;"><b style="font-size: 23px;padding-top: 25px;">51st Foundation Day <br><a style="color: #2E3092; ">Date of press-17/01/2022</a></b><br>
            </div>
        </div>
    </div>
    <div class="container-fluid" style="width: 1410px;background-color:white;height: 25px;">
    </div>
    <div class="container-fluid" style="width:1410px;height: 185px;background-color: #8687ff;">
        <div class="down" style="display: block;">
            <div style="display: inline-block;">
                <img src="./img/down1.png" alt="">
            </div>
            <div style="display: inline-block;margin-left: 150px;">
                <img src="./img/down2.png" alt="">
            </div>
            <div style="display: inline-block;margin-left: 150px;">
                <img src="./img/down3.png" alt="">
            </div>
            <div style="display: inline-block;margin-left: 150px;margin-top: 20px;">
                <img src="./img/down4.png" alt="">
            </div>
        </div>
    </div>
    <div class="container-fluid" style="height:185px;background-color: #E8D6FA;width: 1410px;">
        <img src="./img/logo.png" alt="" style="width: 160px;height: 156px;float: left;padding-top: 20px;">
        <b style="font-size: 40px;">Content Managed by BPRD ,Best viewed in Mozilla, Chrome and equivalent <br> browsers ,Copyright© 2021 All Rights Reserved <br>
            Designed and Developed by .....<u>Pradeesh S</u>.....
            </b>
    </div>
</body>

</html>
```

## OUTPUT:


### Home Page:
![](bprdwebsite\output1.png)
### Menu:
![](bprdwebsite\output2.png)
### Footer:
![](bprdwebsite\output3.png)

## Result:

Thus a website is designed using bootstrap framework.