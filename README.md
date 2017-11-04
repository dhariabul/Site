<!DOCTYPE html>
<html>

<head>
    <title>Ipsoom Center - Silex template</title>
    <meta charset="UTF-8">
    <meta name="generator" content="Silex v2.2.7">
    <!-- leave this for stats -->
    <script type="text/javascript" src="//editor.silex.me/static/2.7/jquery.js" data-silex-static=""></script>
    <script type="text/javascript" src="//editor.silex.me/static/2.7/jquery-ui.js" data-silex-static=""></script>

    <script type="text/javascript" src="//editor.silex.me/static/2.7/pageable.js" data-silex-static=""></script>
    <script type="text/javascript" src="//editor.silex.me/static/2.7/front-end.js" data-silex-static=""></script>
    <!-- Normalize -->
    <link href="//editor.silex.me/static/2.7/normalize.css" rel="stylesheet" data-silex-static="">
    <!-- Silex style -->
    <link href="//editor.silex.me/static/2.7/front-end.css" rel="stylesheet" data-silex-static="">

    <style type="text/css" class="silex-style">
        @import url('//fonts.googleapis.com/css?family=Roboto:100');
        .logo .title {
            color: #FF9900;
        }
        
        .logo .normal {
            color: #FEFFFD;
            font-family: 'Roboto', sans-serif;
            font-size: 60px;
            line-height: 25px;
            min-height: 125px;
            text-transform: uppercase;
        }
        
        .nav .normal {
            color: #FEFFFD;
            font-family: 'Roboto', sans-serif;
            font-size: 18px;
            line-height: 45px;
            text-transform: uppercase;
            z-index: 1;
        }
        
        .nav-mark {
            border-bottom: 1px solid #000000;
            transition: border .2s ease-out, background-color .2s ease-out;
        }
        
        .nav-mark:hover {
            border-bottom: 1px solid #FF9900;
        }
        
        .nav-mark.page-link-active {
            background-color: #FF9900;
        }
        /* home */
        
        .sub-nav.page-link-active {
            width: 250px;
            box-shadow: 0 1px 10px black;
        }
        
        .sub-nav {
            transition: all .15s ease-out;
            color: #FEFFFD;
            font-family: 'Roboto', sans-serif;
            font-size: 25px;
            line-height: 5px;
            text-transform: uppercase;
            z-index: 1;
        }
        
        .sub-nav .heading1 {
            font-size: 40px;
        }
        
        .normal,
        .heading1 {
            color: #FEFFFD;
            font-weight: 200;
            line-height: 20px;
        }
        
        .white-bg .heading2,
        .white-bg .normal {
            color: black;
        }
        
        .white-bg .heading2 {
            font-family: 'Roboto', sans-serif;
            font-weight: 100;
            font-size: 40px;
            text-transform: capitalize;
            line-height: 0px;
        }
        
        .white-bg .heading2:first-letter {
            background-color: #FF9900;
            color: #FEFFFD;
            padding: 0 10px;
            margin-right: 2px;
        }
        
        .white-bg .normal {
            font-size: 15px;
            font-family: Arial, sans-serif;
            line-height: 20px;
        }
        
        .button-read-more .normal {
            font-family: 'Roboto', sans-serif;
            font-weight: 100;
            text-transform: capitalize;
            line-height: 30px;
        }
    </style>
    <script type="text/javascript" class="silex-script"></script>
    <meta name="publicationPath" content="/api/1.0/github/exec/put/silex-templates/wip/ipsoom">
    <style class="silex-inline-styles" type="text/css">
        .silex-id-1439554967896-66 {
            left: 0px;
            top: 0px;
            background-color: rgb(0, 0, 0);
            border-top-color: rgb(0, 0, 0);
            border-right-color: rgb(0, 0, 0);
            border-bottom-color: rgb(0, 0, 0);
            border-left-color: rgb(0, 0, 0);
        }
        
        .silex-id-1490693608162-3 {
            background-color: transparent;
            top: 5px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1490693608161-2 {
            min-height: 157px;
            background-color: transparent;
            top: 15px;
            left: 323px;
            width: 960px;
        }
        
        .silex-id-1439554967492-62 {
            width: 91px;
            top: 2px;
            left: 266px;
            box-sizing: content-box;
            min-height: 136px;
            background-color: rgba(102, 88, 71, 1);
        }
        
        .silex-id-1439554967286-60 {
            width: 148px;
            top: 2px;
            left: 377px;
            box-sizing: content-box;
            min-height: 135px;
            background-color: rgba(102, 88, 71, 1);
        }
        
        .silex-id-1439554966975-57 {
            width: 129px;
            top: 1px;
            left: 546px;
            box-sizing: content-box;
            min-height: 136px;
            background-color: rgba(102, 88, 71, 1);
        }
        
        .silex-id-1439554966767-55 {
            width: 124px;
            top: 1px;
            left: 697px;
            box-sizing: content-box;
            min-height: 136px;
            background-color: rgba(102, 88, 71, 1);
        }
        
        .silex-id-1439554966563-53 {
            width: 114px;
            top: 1px;
            left: 844px;
            box-sizing: content-box;
            min-height: 135px;
            background-color: rgba(102, 88, 71, 1);
        }
        
        .silex-id-1509486793686-1 {
            width: 201px;
            min-height: 100px;
            top: 24px;
            left: 28px;
        }
        
        .silex-id-1490693798023-5 {
            background-color: transparent;
            top: 197px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1490693798022-4 {
            min-height: 482px;
            background-color: transparent;
            top: 15px;
            left: 647px;
            width: 960px;
        }
        
        .silex-id-1439554966458-52 {
            width: 960px;
            top: -14px;
            left: 0px;
            box-sizing: content-box;
            background-color: rgb(0, 0, 0);
            min-height: 483px;
        }
        
        .silex-id-1439554966357-51 {
            width: 232px;
            top: 163px;
            left: 0px;
            box-sizing: content-box;
            border-top-color: rgb(255, 255, 255);
            border-right-color: rgb(255, 255, 255);
            border-bottom-color: rgb(255, 255, 255);
            border-left-color: rgb(255, 255, 255);
            border-top-width: 0px;
            border-right-width: 3px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            background-color: rgb(102, 88, 71);
            min-height: 158px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554966357-51 {
                top: 0px;
                left: 93px;
                width: 234px;
                min-height: 158px;
            }
        }
        
        .silex-id-1439554966255-50 {
            width: 183px;
            top: 22px;
            left: 45px;
            box-sizing: content-box;
            min-height: 118px;
        }
        
        .silex-id-1439554966154-49 {
            width: 232px;
            top: 5px;
            left: 0px;
            box-sizing: content-box;
            border-top-color: rgb(255, 255, 255);
            border-right-color: rgb(255, 255, 255);
            border-bottom-color: rgb(255, 255, 255);
            border-left-color: rgb(255, 255, 255);
            border-top-width: 0px;
            border-right-width: 3px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            background-color: rgb(255, 153, 0);
            min-height: 158px;
        }
        
        .silex-id-1439554966050-48 {
            width: 183px;
            top: 17px;
            left: 45px;
            box-sizing: content-box;
            min-height: 104px;
        }
        
        .silex-id-1439554965843-46 {
            width: 232px;
            top: 321px;
            left: 0px;
            box-sizing: content-box;
            border-top-color: rgb(255, 255, 255);
            border-right-color: rgb(255, 255, 255);
            border-bottom-color: rgb(255, 255, 255);
            border-left-color: rgb(255, 255, 255);
            border-top-width: 0px;
            border-right-width: 3px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            background-color: rgb(61, 54, 45);
            min-height: 158px;
        }
        
        .silex-id-1439554965740-45 {
            width: 183px;
            top: 22px;
            left: 45px;
            box-sizing: content-box;
            min-height: 104px;
        }
        
        .silex-id-1439554965638-44 {
            width: 726px;
            top: 5px;
            left: 232px;
            box-sizing: content-box;
            background-image: url('content_bg.jpg');
            background-color: transparent;
            background-size: cover;
            min-height: 474px;
        }
        
        .silex-id-1509488264236-2 {
            width: 626px;
            min-height: 303px;
            top: 141px;
            left: 75px;
        }
        
        .silex-id-1439554965536-43 {
            width: 726px;
            top: 6px;
            left: 233px;
            box-sizing: content-box;
            background-image: url('homebg.jpg');
            background-color: transparent;
            background-size: cover;
            min-height: 474px;
        }
        
        .silex-id-1439554964112-29 {
            width: 655px;
            top: 353px;
            left: 36px;
            box-sizing: content-box;
            min-height: 111px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964112-29 {
                top: 1183px;
                left: 57px;
                width: 331px;
                min-height: 172px;
            }
        }
        
        .silex-id-1439554965947-47 {
            width: 726px;
            top: -10px;
            left: 232px;
            box-sizing: content-box;
            background-image: url('efforts_bg.jpg');
            background-color: transparent;
            background-size: cover;
            min-height: 474px;
        }
        
        .silex-id-1509488761358-3 {
            width: 643px;
            min-height: 180px;
            top: 52px;
            left: 69px;
        }
        
        .silex-id-1509488811707-4 {
            width: 626px;
            min-height: 160px;
            top: 270px;
            left: 69px;
        }
        
        .silex-id-1490693931165-7 {
            background-color: transparent;
            top: 714px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1490693931163-6 {
            min-height: 366px;
            background-color: transparent;
            top: 15px;
            left: 323px;
            width: 960px;
        }
        
        .silex-id-1439554965432-42 {
            width: 960px;
            top: -9px;
            left: 0px;
            box-sizing: content-box;
            background-color: rgb(254, 255, 253);
            min-height: 309px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965432-42 {
                top: 141px;
                left: 11px;
                width: 423px;
                min-height: 979px;
            }
        }
        
        .silex-id-1439554965331-41 {
            width: 290px;
            top: 26px;
            left: 37px;
            box-sizing: content-box;
            border-top-width: 0px;
            border-right-width: 1px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(102, 88, 71);
            border-right-color: rgb(102, 88, 71);
            border-bottom-color: rgb(102, 88, 71);
            border-left-color: rgb(102, 88, 71);
            background-color: transparent;
            min-height: 254px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965331-41 {
                top: 32px;
                left: 10px;
                width: 402px;
                min-height: 262px;
            }
        }
        
        .silex-id-1509489030003-5 {
            width: 288px;
            min-height: 27px;
            top: 3px;
            left: 1px;
        }
        
        .silex-id-1439554962386-12 {
            width: 25px;
            top: -3px;
            left: -2px;
            box-sizing: content-box;
            min-height: 34.5676px;
        }
        
        .silex-id-1509489255761-8 {
            width: 286px;
            min-height: 170px;
            top: 57px;
            left: 2px;
        }
        
        .silex-id-1439554964925-37 {
            width: 290px;
            top: 26px;
            left: 345px;
            box-sizing: content-box;
            border-top-width: 0px;
            border-right-width: 1px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(102, 88, 71);
            border-right-color: rgb(102, 88, 71);
            border-bottom-color: rgb(102, 88, 71);
            border-left-color: rgb(102, 88, 71);
            background-color: transparent;
            min-height: 254px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964925-37 {
                top: 359px;
                left: 10px;
                width: 402px;
                min-height: 262px;
            }
        }
        
        .silex-id-1509489096770-6 {
            width: 288px;
            min-height: 27px;
            top: 3px;
            left: 1px;
        }
        
        .silex-id-1509489283694-9 {
            width: 286px;
            min-height: 170px;
            top: 55px;
            left: 3px;
        }
        
        .silex-id-1509569771473-0 {
            width: 25px;
            top: -3px;
            left: 24px;
            box-sizing: content-box;
            min-height: 34.5676px;
        }
        
        .silex-id-1439554964518-33 {
            width: 290px;
            top: 26px;
            left: 656px;
            box-sizing: content-box;
            border-top-color: rgb(102, 88, 71);
            border-right-color: rgb(102, 88, 71);
            border-bottom-color: rgb(102, 88, 71);
            border-left-color: rgb(102, 88, 71);
            background-color: transparent;
            min-height: 254px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964518-33 {
                top: 685px;
                left: 11px;
                width: 414px;
                min-height: 262px;
            }
        }
        
        .silex-id-1509489102676-7 {
            width: 288px;
            min-height: 27px;
            top: 3px;
            left: 2px;
        }
        
        .silex-id-1509489291973-10 {
            width: 286px;
            min-height: 170px;
            top: 56px;
            left: 2px;
        }
        
        .silex-id-1509569784167-1 {
            width: 25px;
            top: -2px;
            left: 15px;
            box-sizing: content-box;
            min-height: 34.5676px;
        }
        
        .silex-id-1490694152451-11 {
            background-color: transparent;
            top: 433px;
            left: NaNpx;
            min-width: 960px;
        }
        
        .silex-id-1490694152449-10 {
            min-height: 236px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1439554961635-5 {
            width: 817px;
            top: 31px;
            left: 2px;
            box-sizing: content-box;
            min-height: 189px;
        }
        
        .silex-id-1490701849669-19 {
            background-color: transparent;
            top: 159px;
            left: 0px;
            min-width: 960px;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/UJO0jYLtRte4qpyA37Xu_9X6A7388.jpg');
            background-size: cover;
            background-position: center center;
        }
        
        .silex-id-1490701849668-18 {
            min-height: 480px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1490694237194-15 {
            background-color: transparent;
            top: 171px;
            left: 0px;
            min-width: 960px;
        }
        
        .silex-id-1490694237193-14 {
            min-height: 232px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1439554961331-2 {
            width: 817px;
            top: 31px;
            left: 2px;
            box-sizing: content-box;
            min-height: 189px;
        }
        
        .silex-id-1490701944668-23 {
            background-color: transparent;
            top: 100px;
            left: NaNpx;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/xpdPwXTASnOUXFpIPgDs_IMG_1460_edt.jpg');
            background-size: cover;
            background-position: bottom center;
        }
        
        .silex-id-1490701944667-22 {
            min-height: 480px;
            background-color: transparent;
        }
        
        .silex-id-1490694258064-17 {
            background-color: transparent;
            top: 171px;
            left: 0px;
            border-color: #000000;
            min-width: 960px;
        }
        
        .silex-id-1490694258062-16 {
            min-height: 744px;
            background-color: transparent;
            border-color: #000000;
            top: 15px;
            left: 329px;
            width: 960px;
        }
        
        .silex-id-1492776401689-1 {
            width: 456px;
            height: 587px;
            background-color: transparent;
            top: 83px;
            left: 1px;
        }
        
        .silex-id-1492776672785-2 {
            height: 571px;
            width: 472px;
            background-color: transparent;
            top: 91px;
            left: 487px;
            border-width: 1px 1px 1px 1px;
            border-style: solid;
            border-color: #ffffff;
        }
        
        .silex-id-1509571589425-15 {
            background-color: transparent;
            top: 197px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1509571589426-16 {
            min-height: 72px;
            background-color: transparent;
            top: 15px;
            left: 323px;
            width: 960px;
        }
        
        .silex-id-1509571589426-17 {
            width: 960px;
            top: -7px;
            left: 0px;
            box-sizing: content-box;
            background-color: rgba(255, 153, 0, 1);
            min-height: 67px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1509571589426-17 {
                top: 141px;
                left: 11px;
                width: 423px;
                min-height: 979px;
            }
        }
        
        .silex-id-1509571705685-30 {
            width: 374px;
            min-height: 76px;
            top: 6px;
            left: 292px;
        }
        
        .silex-id-1509729107864-36 {
            min-width: 960px;
            top: 304px;
            left: 5px;
        }
        
        .silex-id-1509729107864-35 {
            width: 960px;
            background-color: rgba(254, 255, 253, 1);
            min-height: 712px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509730790091-43 {
            width: 916px;
            min-height: 145px;
            top: 22px;
            left: 20px;
        }
        
        .silex-id-1509732400668-47 {
            width: 878px;
            min-height: 411px;
            top: 263px;
            left: 41px;
        }
        
        .silex-id-1509732506568-48 {
            width: 875px;
            min-height: 20px;
            top: 681px;
            left: 43px;
        }
        
        .silex-id-1509773825344-49 {
            width: 541px;
            background-color: rgba(255, 255, 255, 1);
            min-height: 22px;
            top: 209px;
            left: 195px;
        }
        
        .silex-id-1509730767790-42 {
            top: 515px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1509730767789-41 {
            width: 960px;
            min-height: 20px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509775843632-83 {
            top: 197px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1509775843631-82 {
            width: 960px;
            min-height: 72px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509775896415-84 {
            width: 960px;
            top: -7px;
            left: 0px;
            box-sizing: content-box;
            background-color: rgba(255, 153, 0, 1);
            min-height: 67px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1509775896415-84 {
                top: 141px;
                left: 11px;
                width: 423px;
                min-height: 979px;
            }
        }
        
        .silex-id-1509776686937-87 {
            width: 452px;
            min-height: 79px;
            top: 6px;
            left: 252px;
        }
        
        .silex-id-1509774845491-57 {
            min-width: 960px;
            top: 304px;
            left: 5px;
        }
        
        .silex-id-1509774845491-58 {
            width: 960px;
            background-color: rgba(254, 255, 253, 1);
            min-height: 230px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509774845492-60 {
            width: 325px;
            min-height: 189px;
            top: 22px;
            left: 19px;
        }
        
        .silex-id-1509774998149-67 {
            width: 580px;
            min-height: 23px;
            top: 24px;
            left: 362px;
            background-color: rgba(208, 208, 208, 1);
        }
        
        .silex-id-1509774845492-59 {
            width: 579px;
            min-height: 107px;
            top: 65px;
            left: 362px;
            background-color: rgba(255, 182, 49, 0.33725490196078434);
        }
        
        .silex-id-1509774845492-62 {
            width: 269px;
            background-color: rgba(255, 255, 255, 1);
            min-height: 23px;
            top: 186px;
            left: 529px;
        }
        
        .silex-id-1509774845497-63 {
            top: 328px;
            left: NaNpx;
            min-width: 960px;
        }
        
        .silex-id-1509774845497-64 {
            width: 960px;
            min-height: 20px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509776784490-88 {
            min-width: 960px;
            top: 100px;
            left: NaNpx;
        }
        
        .silex-id-1509776784491-89 {
            width: 960px;
            background-color: rgba(254, 255, 253, 1);
            min-height: 230px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509776784491-90 {
            width: 325px;
            min-height: 189px;
            top: 22px;
            left: 19px;
        }
        
        .silex-id-1509776784492-91 {
            width: 580px;
            min-height: 23px;
            top: 24px;
            left: 362px;
            background-color: rgba(208, 208, 208, 1);
        }
        
        .silex-id-1509776784492-92 {
            width: 579px;
            min-height: 107px;
            top: 65px;
            left: 362px;
            background-color: rgba(255, 182, 49, 0.33725490196078434);
        }
        
        .silex-id-1509776784492-93 {
            width: 269px;
            background-color: rgba(255, 255, 255, 1);
            min-height: 23px;
            top: 186px;
            left: 529px;
        }
        
        .silex-id-1509777005257-94 {
            top: 200px;
            left: NaNpx;
            min-width: 960px;
        }
        
        .silex-id-1509777005257-95 {
            width: 960px;
            min-height: 20px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509777011264-96 {
            min-width: 960px;
            top: 249px;
            left: NaNpx;
        }
        
        .silex-id-1509777011264-97 {
            width: 960px;
            background-color: rgba(254, 255, 253, 1);
            min-height: 230px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509777011264-98 {
            width: 325px;
            min-height: 189px;
            top: 22px;
            left: 19px;
        }
        
        .silex-id-1509777011265-99 {
            width: 580px;
            min-height: 23px;
            top: 24px;
            left: 362px;
            background-color: rgba(208, 208, 208, 1);
        }
        
        .silex-id-1509777011265-100 {
            width: 579px;
            min-height: 107px;
            top: 65px;
            left: 362px;
            background-color: rgba(255, 182, 49, 0.33725490196078434);
        }
        
        .silex-id-1509777011266-101 {
            width: 269px;
            background-color: rgba(255, 255, 255, 1);
            min-height: 23px;
            top: 186px;
            left: 529px;
        }
        
        .silex-id-1509778750982-102 {
            top: 514px;
            left: NaNpx;
            min-width: 960px;
        }
        
        .silex-id-1509778750982-103 {
            width: 960px;
            min-height: 20px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509778754240-104 {
            min-width: 960px;
            top: 569px;
            left: NaNpx;
        }
        
        .silex-id-1509778754241-105 {
            width: 960px;
            background-color: rgba(254, 255, 253, 1);
            min-height: 230px;
            top: 15px;
            left: 323px;
        }
        
        .silex-id-1509778754241-106 {
            width: 325px;
            min-height: 189px;
            top: 22px;
            left: 19px;
        }
        
        .silex-id-1509778754241-107 {
            width: 580px;
            min-height: 23px;
            top: 24px;
            left: 362px;
            background-color: rgba(208, 208, 208, 1);
        }
        
        .silex-id-1509778754242-108 {
            width: 579px;
            min-height: 107px;
            top: 65px;
            left: 362px;
            background-color: rgba(255, 182, 49, 0.33725490196078434);
        }
        
        .silex-id-1509778754242-109 {
            width: 269px;
            background-color: rgba(255, 255, 255, 1);
            min-height: 23px;
            top: 186px;
            left: 529px;
        }
        
        .silex-id-1509778854467-110 {
            top: 834px;
            left: NaNpx;
            min-width: 960px;
        }
        
        .silex-id-1509778854468-111 {
            width: 960px;
            min-height: 20px;
            top: 15px;
            left: 323px;
        }
    </style>




























    <script type="text/javascript" class="silex-json-styles">
        [{"desktop":{"silex-id-1439554967896-66":{"left":"0px","top":"0px","background-color":"rgb(0, 0, 0)","border-top-color":"rgb(0, 0, 0)","border-right-color":"rgb(0, 0, 0)","border-bottom-color":"rgb(0, 0, 0)","border-left-color":"rgb(0, 0, 0)"},"silex-id-1439554967492-62":{"width":"91px","top":"2px","left":"266px","box-sizing":"content-box","min-height":"136px","background-color":"rgba(102,88,71,1)"},"silex-id-1439554967286-60":{"width":"148px","top":"2px","left":"377px","box-sizing":"content-box","min-height":"135px","background-color":"rgba(102,88,71,1)"},"silex-id-1439554966975-57":{"width":"129px","top":"1px","left":"546px","box-sizing":"content-box","min-height":"136px","background-color":"rgba(102,88,71,1)"},"silex-id-1439554966767-55":{"width":"124px","top":"1px","left":"697px","box-sizing":"content-box","min-height":"136px","background-color":"rgba(102,88,71,1)"},"silex-id-1439554966563-53":{"width":"114px","top":"1px","left":"844px","box-sizing":"content-box","min-height":"135px","background-color":"rgba(102,88,71,1)"},"silex-id-1439554966458-52":{"width":"960px","top":"-14px","left":"0px","box-sizing":"content-box","background-color":"rgb(0, 0, 0)","min-height":"483px"},"silex-id-1439554966357-51":{"width":"232px","top":"163px","left":"0px","box-sizing":"content-box","border-top-color":"rgb(255, 255, 255)","border-right-color":"rgb(255, 255, 255)","border-bottom-color":"rgb(255, 255, 255)","border-left-color":"rgb(255, 255, 255)","border-top-width":"0px","border-right-width":"3px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","background-color":"rgb(102, 88, 71)","min-height":"158px"},"silex-id-1439554966255-50":{"width":"183px","top":"22px","left":"45px","box-sizing":"content-box","min-height":"118px"},"silex-id-1439554966154-49":{"width":"232px","top":"5px","left":"0px","box-sizing":"content-box","border-top-color":"rgb(255, 255, 255)","border-right-color":"rgb(255, 255, 255)","border-bottom-color":"rgb(255, 255, 255)","border-left-color":"rgb(255, 255, 255)","border-top-width":"0px","border-right-width":"3px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","background-color":"rgb(255, 153, 0)","min-height":"158px"},"silex-id-1439554966050-48":{"width":"183px","top":"17px","left":"45px","box-sizing":"content-box","min-height":"104px"},"silex-id-1439554965947-47":{"width":"726px","top":"-10px","left":"232px","box-sizing":"content-box","background-image":"url('efforts_bg.jpg')","background-color":"transparent","background-size":"cover","min-height":"474px"},"silex-id-1439554965843-46":{"width":"232px","top":"321px","left":"0px","box-sizing":"content-box","border-top-color":"rgb(255, 255, 255)","border-right-color":"rgb(255, 255, 255)","border-bottom-color":"rgb(255, 255, 255)","border-left-color":"rgb(255, 255, 255)","border-top-width":"0px","border-right-width":"3px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","background-color":"rgb(61, 54, 45)","min-height":"158px"},"silex-id-1439554965740-45":{"width":"183px","top":"22px","left":"45px","box-sizing":"content-box","min-height":"104px"},"silex-id-1439554965638-44":{"width":"726px","top":"5px","left":"232px","box-sizing":"content-box","background-image":"url('content_bg.jpg')","background-color":"transparent","background-size":"cover","min-height":"474px"},"silex-id-1439554965536-43":{"width":"726px","top":"6px","left":"233px","box-sizing":"content-box","background-image":"url('homebg.jpg')","background-color":"transparent","background-size":"cover","min-height":"474px"},"silex-id-1439554965432-42":{"width":"960px","top":"-9px","left":"0px","box-sizing":"content-box","background-color":"rgb(254, 255, 253)","min-height":"309px"},"silex-id-1439554965331-41":{"width":"290px","top":"26px","left":"37px","box-sizing":"content-box","border-top-width":"0px","border-right-width":"1px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(102, 88, 71)","border-right-color":"rgb(102, 88, 71)","border-bottom-color":"rgb(102, 88, 71)","border-left-color":"rgb(102, 88, 71)","background-color":"transparent","min-height":"254px"},"silex-id-1439554964925-37":{"width":"290px","top":"26px","left":"345px","box-sizing":"content-box","border-top-width":"0px","border-right-width":"1px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(102, 88, 71)","border-right-color":"rgb(102, 88, 71)","border-bottom-color":"rgb(102, 88, 71)","border-left-color":"rgb(102, 88, 71)","background-color":"transparent","min-height":"254px"},"silex-id-1439554964518-33":{"width":"290px","top":"26px","left":"656px","box-sizing":"content-box","border-top-color":"rgb(102, 88, 71)","border-right-color":"rgb(102, 88, 71)","border-bottom-color":"rgb(102, 88, 71)","border-left-color":"rgb(102, 88, 71)","background-color":"transparent","min-height":"254px"},"silex-id-1439554964112-29":{"width":"655px","top":"353px","left":"36px","box-sizing":"content-box","min-height":"111px"},"silex-id-1439554963605-24":{"width":"276px","top":"14px","left":"14px","box-sizing":"content-box","min-height":"147px"},"silex-id-1439554963502-23":{"width":"113px","top":"166px","left":"16px","box-sizing":"content-box","background-color":"rgba(102,88,71,1)","min-height":"34px"},"silex-id-1439554963298-21":{"width":"276px","top":"14px","left":"14px","box-sizing":"content-box","min-height":"147px"},"silex-id-1439554963198-20":{"width":"113px","top":"166px","left":"16px","box-sizing":"content-box","background-color":"rgb(102, 88, 71)","min-height":"34px"},"silex-id-1439554962792-16":{"width":"600px","top":"208px","left":"180px","box-sizing":"content-box","background-color":"transparent","min-height":"50px"},"silex-id-1439554962691-15":{"width":"264px","top":"85px","left":"37px","box-sizing":"content-box","min-height":"67px"},"silex-id-1439554962589-14":{"width":"88px","top":"88px","left":"834px","min-height":"37px"},"silex-id-1439554962488-13":{"width":"40px","top":"86px","left":"771px","min-height":"40px"},"silex-id-1439554962386-12":{"width":"25px","top":"-3px","left":"-2px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1439554962181-10":{"width":"102px","top":"136px","left":"539px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554962078-9":{"width":"133px","top":"136px","left":"400px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961964-8":{"width":"146px","top":"136px","left":"247px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961840-7":{"width":"134px","top":"136px","left":"107px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961739-6":{"width":"65px","top":"136px","left":"37px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961635-5":{"width":"817px","top":"31px","left":"2px","box-sizing":"content-box","min-height":"189px"},"silex-id-1439554961533-4":{"width":"726px","top":"321px","left":"2px","min-height":"474px"},"silex-id-1439554961432-3":{"width":"817px","top":"31px","left":"2px","box-sizing":"content-box","min-height":"189px"},"silex-id-1439554961331-2":{"width":"817px","top":"31px","left":"2px","box-sizing":"content-box","min-height":"189px"},"silex-id-1439554961229-1":{"width":"100px","top":"378px","left":"288px","background-color":"transparent","min-height":"100px"},"silex-id-1490693608161-2":{"min-height":"157px","background-color":"transparent","top":"15px","left":"323px","width":"960px"},"silex-id-1490693608162-3":{"background-color":"transparent","top":"5px","left":"5px","min-width":"960px"},"silex-id-1490693798022-4":{"min-height":"482px","background-color":"transparent","top":"15px","left":"647px","width":"960px"},"silex-id-1490693798023-5":{"background-color":"transparent","top":"197px","left":"5px","min-width":"960px"},"silex-id-1490693931163-6":{"min-height":"366px","background-color":"transparent","top":"15px","left":"323px","width":"960px"},"silex-id-1490693931165-7":{"background-color":"transparent","top":"714px","left":"5px","min-width":"960px"},"silex-id-1490694042604-8":{"min-height":"269px","background-color":"transparent"},"silex-id-1490694152449-10":{"min-height":"236px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490694152451-11":{"background-color":"transparent","top":"433px","left":"NaNpx","min-width":"960px"},"silex-id-1490694217944-12":{"min-height":"236px","background-color":"transparent"},"silex-id-1490694237193-14":{"min-height":"232px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490694237194-15":{"background-color":"transparent","top":"171px","left":"0px","min-width":"960px"},"silex-id-1490694258062-16":{"min-height":"744px","background-color":"transparent","border-width":"","border-style":"","border-color":"#000000","top":"15px","left":"329px","width":"960px"},"silex-id-1490694258064-17":{"background-color":"transparent","top":"171px","left":"0px","border-color":"#000000","min-width":"960px"},"silex-id-1490701849668-18":{"min-height":"480px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490701849669-19":{"background-color":"transparent","top":"159px","left":"0px","min-width":"960px","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/UJO0jYLtRte4qpyA37Xu_9X6A7388.jpg')","background-size":"cover","background-position":"center center"},"silex-id-1490701905043-20":{"min-height":"480px","background-color":"transparent"},"silex-id-1490701944667-22":{"min-height":"480px","background-color":"transparent"},"silex-id-1490701944668-23":{"background-color":"transparent","top":"100px","left":"NaNpx","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/xpdPwXTASnOUXFpIPgDs_IMG_1460_edt.jpg')","background-size":"cover","background-position":"bottom center"},"silex-id-1492776401689-1":{"width":"456px","height":"587px","background-color":"transparent","top":"83px","left":"1px"},"silex-id-1492776672785-2":{"height":"571px","width":"472px","background-color":"transparent","top":"91px","left":"487px","border-width":"1px 1px 1px 1px ","border-style":"solid","border-color":"#ffffff"},"silex-id-1509486793686-1":{"width":"201px","min-height":"100px","top":"24px","left":"28px"},"silex-id-1509488264236-2":{"width":"626px","min-height":"303px","top":"141px","left":"75px"},"silex-id-1509488761358-3":{"width":"643px","min-height":"180px","top":"52px","left":"69px"},"silex-id-1509488811707-4":{"width":"626px","min-height":"160px","top":"270px","left":"69px"},"silex-id-1509489030003-5":{"width":"288px","min-height":"27px","top":"3px","left":"1px"},"silex-id-1509489096770-6":{"width":"288px","min-height":"27px","top":"3px","left":"1px"},"silex-id-1509489102676-7":{"width":"288px","min-height":"27px","top":"3px","left":"2px"},"silex-id-1509489255761-8":{"width":"286px","min-height":"170px","top":"57px","left":"2px"},"silex-id-1509489283694-9":{"width":"286px","min-height":"170px","top":"55px","left":"3px"},"silex-id-1509489291973-10":{"width":"286px","min-height":"170px","top":"56px","left":"2px"},"silex-id-1509569771473-0":{"width":"25px","top":"-3px","left":"24px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1509569784167-1":{"width":"25px","top":"-2px","left":"15px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1509571411155-4":{"width":"288px","min-height":"27px","top":"3px","left":"1px"},"silex-id-1509571411155-5":{"width":"25px","top":"-3px","left":"-2px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1509571411155-6":{"width":"286px","min-height":"170px","top":"57px","left":"2px"},"silex-id-1509571589426-19":{"width":"288px","min-height":"27px","top":"3px","left":"1px"},"silex-id-1509571589426-20":{"width":"25px","top":"-3px","left":"-2px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1509571589427-21":{"width":"286px","min-height":"170px","top":"57px","left":"2px"},"silex-id-1509571589431-29":{"width":"25px","top":"-2px","left":"15px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1509571589426-17":{"width":"960px","top":"-7px","left":"0px","box-sizing":"content-box","background-color":"rgba(255,153,0,1)","min-height":"67px"},"silex-id-1509571589425-15":{"background-color":"transparent","top":"197px","left":"5px","min-width":"960px"},"silex-id-1509571589426-16":{"min-height":"72px","background-color":"transparent","top":"15px","left":"323px","width":"960px"},"silex-id-1509571705685-30":{"width":"374px","min-height":"76px","top":"6px","left":"292px"},"silex-id-1509729107864-35":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"712px","top":"15px","left":"323px"},"silex-id-1509729107864-36":{"min-width":"960px","top":"304px","left":"5px"},"silex-id-1509730668116-38":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"116px","top":"15px","left":"323px"},"silex-id-1509730742090-40":{"width":"374px","min-height":"76px","top":"6px","left":"292px"},"silex-id-1509730742090-39":{"width":"960px","top":"13px","left":"-2px","box-sizing":"content-box","background-color":"rgba(255,153,0,1)","min-height":"67px"},"silex-id-1509730767789-41":{"width":"960px","background-color":"","min-height":"20px","top":"15px","left":"323px"},"silex-id-1509730767790-42":{"top":"515px","left":"5px","min-width":"960px"},"silex-id-1509730790091-43":{"width":"916px","min-height":"145px","top":"22px","left":"20px"},"silex-id-1509731632740-46":{"width":"859px","min-height":"26px","top":"17px","left":"49px","opacity":""},"silex-id-1509731632739-45":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"54px","top":"15px","left":"323px"},"silex-id-1509732400668-47":{"width":"878px","min-height":"411px","top":"263px","left":"41px"},"silex-id-1509732506568-48":{"width":"875px","min-height":"20px","top":"681px","left":"43px"},"silex-id-1509773825344-49":{"width":"541px","background-color":"rgba(255,255,255,1)","min-height":"22px","top":"209px","left":"195px"},"silex-id-1509774845469-56":{"width":"374px","min-height":"76px","top":"6px","left":"292px"},"silex-id-1509774845469-55":{"width":"960px","top":"-7px","left":"0px","box-sizing":"content-box","background-color":"rgba(255,153,0,1)","min-height":"67px"},"silex-id-1509774845468-54":{"min-height":"194px","background-color":"transparent","top":"15px","left":"323px","width":"960px"},"silex-id-1509774845492-59":{"width":"579px","min-height":"107px","top":"65px","left":"362px","background-color":"rgba(255,182,49,0.33725490196078434)"},"silex-id-1509774845492-60":{"width":"325px","min-height":"189px","top":"22px","left":"19px"},"silex-id-1509774845492-62":{"width":"269px","background-color":"rgba(255,255,255,1)","min-height":"23px","top":"186px","left":"529px"},"silex-id-1509774845491-57":{"min-width":"960px","top":"304px","left":"5px"},"silex-id-1509774845491-58":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"230px","top":"15px","left":"323px"},"silex-id-1509774845497-63":{"top":"328px","left":"NaNpx","min-width":"960px"},"silex-id-1509774845497-64":{"width":"960px","background-color":"","min-height":"20px","top":"15px","left":"323px"},"silex-id-1509774869054-66":{"width":"374px","min-height":"76px","top":"6px","left":"292px"},"silex-id-1509774998149-67":{"width":"580px","min-height":"23px","top":"24px","left":"362px","background-color":"rgba(208,208,208,1)"},"silex-id-1509775689284-81":{"width":"374px","min-height":"76px","top":"6px","left":"292px"},"silex-id-1509775843631-82":{"width":"960px","background-color":"","min-height":"72px","top":"15px","left":"323px"},"silex-id-1509775843632-83":{"top":"197px","left":"5px","min-width":"960px"},"silex-id-1509775896415-84":{"width":"960px","top":"-7px","left":"0px","box-sizing":"content-box","background-color":"rgba(255,153,0,1)","min-height":"67px"},"silex-id-1509776686937-87":{"width":"452px","min-height":"79px","top":"6px","left":"252px"},"silex-id-1509776784491-90":{"width":"325px","min-height":"189px","top":"22px","left":"19px"},"silex-id-1509776784492-91":{"width":"580px","min-height":"23px","top":"24px","left":"362px","background-color":"rgba(208,208,208,1)"},"silex-id-1509776784492-92":{"width":"579px","min-height":"107px","top":"65px","left":"362px","background-color":"rgba(255,182,49,0.33725490196078434)"},"silex-id-1509776784492-93":{"width":"269px","background-color":"rgba(255,255,255,1)","min-height":"23px","top":"186px","left":"529px"},"silex-id-1509776784490-88":{"min-width":"960px","top":"100px","left":"NaNpx"},"silex-id-1509776784491-89":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"230px","top":"15px","left":"323px"},"silex-id-1509777005257-94":{"top":"200px","left":"NaNpx","min-width":"960px"},"silex-id-1509777005257-95":{"width":"960px","background-color":"","min-height":"20px","top":"15px","left":"323px"},"silex-id-1509777011264-98":{"width":"325px","min-height":"189px","top":"22px","left":"19px"},"silex-id-1509777011265-99":{"width":"580px","min-height":"23px","top":"24px","left":"362px","background-color":"rgba(208,208,208,1)"},"silex-id-1509777011265-100":{"width":"579px","min-height":"107px","top":"65px","left":"362px","background-color":"rgba(255,182,49,0.33725490196078434)"},"silex-id-1509777011266-101":{"width":"269px","background-color":"rgba(255,255,255,1)","min-height":"23px","top":"186px","left":"529px"},"silex-id-1509777011264-96":{"min-width":"960px","top":"249px","left":"NaNpx"},"silex-id-1509777011264-97":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"230px","top":"15px","left":"323px"},"silex-id-1509778750982-102":{"top":"514px","left":"NaNpx","min-width":"960px"},"silex-id-1509778750982-103":{"width":"960px","background-color":"","min-height":"20px","top":"15px","left":"323px"},"silex-id-1509778754241-106":{"width":"325px","min-height":"189px","top":"22px","left":"19px"},"silex-id-1509778754241-107":{"width":"580px","min-height":"23px","top":"24px","left":"362px","background-color":"rgba(208,208,208,1)"},"silex-id-1509778754242-108":{"width":"579px","min-height":"107px","top":"65px","left":"362px","background-color":"rgba(255,182,49,0.33725490196078434)"},"silex-id-1509778754242-109":{"width":"269px","background-color":"rgba(255,255,255,1)","min-height":"23px","top":"186px","left":"529px"},"silex-id-1509778754240-104":{"min-width":"960px","top":"569px","left":"NaNpx"},"silex-id-1509778754241-105":{"width":"960px","background-color":"rgba(254,255,253,1)","min-height":"230px","top":"15px","left":"323px"},"silex-id-1509778854467-110":{"top":"834px","left":"NaNpx","min-width":"960px"},"silex-id-1509778854468-111":{"width":"960px","background-color":"","min-height":"20px","top":"15px","left":"323px"}},"mobile":{"silex-id-1439554965432-42":{"top":"141px","left":"11px","width":"423px","min-height":"979px"},"silex-id-1439554964112-29":{"top":"1183px","left":"57px","width":"331px","min-height":"172px"},"silex-id-1439554962691-15":{"top":"2000px","left":"13px","width":"419px","min-height":"125px"},"silex-id-1439554966357-51":{"top":"0px","left":"93px","width":"234px","min-height":"158px"},"silex-id-1439554965331-41":{"top":"32px","left":"10px","width":"402px","min-height":"262px"},"silex-id-1439554964925-37":{"top":"359px","left":"10px","width":"402px","min-height":"262px"},"silex-id-1439554964518-33":{"top":"685px","left":"11px","width":"414px","min-height":"262px"},"silex-id-1439554961533-4":{"top":"797px","left":"11px","width":"423px","min-height":"307px"},"silex-id-1439554963605-24":{"top":"5px","left":"11px","width":"401px","min-height":"160px"},"silex-id-1439554963298-21":{"top":"5px","left":"11px","width":"401px","min-height":"160px"},"silex-id-1509571589426-17":{"top":"141px","left":"11px","width":"423px","min-height":"979px"},"silex-id-1509730742090-39":{"top":"141px","left":"11px","width":"423px","min-height":"979px"},"silex-id-1509774845469-55":{"top":"141px","left":"11px","width":"423px","min-height":"979px"},"silex-id-1509775896415-84":{"top":"141px","left":"11px","width":"423px","min-height":"979px"}},"componentData":{"silex-id-1492776401689-1":{"name":"form1","templateName":"form","field1":false,"label1":"","label2":"","label3":"","placeholder3":"Your Message"},"silex-id-1492776672785-2":{"name":"map1","templateName":"map"}}}]
    </script>




    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=2.2" data-silex-viewport="">

















































    <script src="//editor.silex.me/static/2.7/osm/ol.js" data-dependency=""></script>




















































    <style id="current-page-style">
        .page-learning-videos {
            display: inherit;
        }
    </style>
    <!-- Silex HEAD tag do not remove -->
    <!-- End of Silex HEAD tag do not remove -->
</head>

<body data-silex-type="container" class="silex-id-1439554967896-66 enable-mobile gform silex-runtime" data-silex-id="silex-id-1439554967896-66">














    <div class=""></div>




























    <div class="silex-pages">
        <div data-silex-type="image" data-silex-id="silex-id-hamburger-menu" class="menu-button editable-style silex-id-hamburger-menu image-element page-page-1 paged-element prevent-draggable prevent-resizable"><img alt="open mobile menu" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAoCAYAAAC8cqlMAAAB5UlEQVR42u2ZPWvCUBSGM+UfFO3e3dLu/QN+oKj4EUXRQREEJYgoiCAu6qCogyDo7iJ21UUaKqEgCC4iiEMGB3UVgsnpTWj/wfVK2nvhGbKEPJyT996TMMzPGg6H5mKx+GgkyuWyeTQasb8OTDwef4tEIp8+n+/LYIjJZJJHQiwzm81M6OLDarWqNpsNjEYgEJCy2ewT0+/3TagighElNFAnQT6ft1ARKkJFqMgfFvF4PFpuEwFtdrcRqVarIIoirFYrIiyXSxiPx+B2u/GJBINBuF6vQHopigK1Wg2fCMdxcLlciIuoqgqNRgOfiN1uB3Qwg91uB8fjkQiHwwEmkwne1qLxS0VuKKJle71eh06nQ4Rmswk8z+MVcTqdsNlsQJZlotF7Pp8hk8ngE4lGo/qN7xG/vV4Pb0Xm8zlxkdPpBGgMx/+yJxIJKBQKRMjlcuBwOGhq/Q+RcDgMsViMCFrAuFwu/CKDwQC22y1IkkSE/X4PgiDo+xc2Ea0S9zjGa/Hb7Xbxifj9fj0K7yFSqVTwtlY6nYbpdKpPiSRYLBbQarX0PYymFhWhIlSEilCRW6GdyUqlkoVZr9dsKpXiOY6TtW+7BkNBz/7ebrcf9L+6Xq+XRYPMMyrTq5EIhUIvaAjTJb4BBNQ2yhnth0wAAAAASUVORK5CYII="
                class="silex-element-content"></div><a id="page-home" data-silex-type="page" class="page-element">Home</a><a id="page-content" data-silex-type="page" class="page-element">content</a><a id="page-efforts" data-silex-type="page" class="page-element">efforts</a>
        <a id="page-our-mission" data-silex-type="page" class="page-element">Our Mission</a><a id="page-learning-videos" data-silex-type="page" class="page-element page-link-active">learning videos</a><a id="page-how-to-help" data-silex-type="page" class="page-element">How to Help</a>
        <a id="page-contact" data-silex-type="page" class="page-element">Contact</a>
        <a id="page-menu" data-silex-type="page" class="page-element">Menu</a></div>
























































































































    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490693608162-3 section-element hide-on-mobile" data-silex-id="silex-id-1490693608162-3">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490693608161-2 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490693608161-2">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554967492-62 nav nav-mark" data-silex-id="silex-id-1439554967492-62" data-silex-href="#!page-home" style="">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">
                        <font size="3"><b>Home<br></b><br></font>
                    </div>
                    <div style="text-align: center;">
                        <font size="3">الرئيسية</font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554967286-60 nav nav-mark" data-silex-id="silex-id-1439554967286-60" data-silex-href="#!page-our-mission" style="">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">
                        <font size="3"><b style="">eXPLANATIONS MATERIALS</b>
                        </font>
                    </div>
                    <div style="text-align: center;">
                        <font size="3">المستندات التوضيحية</font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554966975-57 nav nav-mark page-link-active" data-silex-id="silex-id-1439554966975-57" data-silex-href="#!page-learning-videos" style="">
                <div class="silex-element-content normal">
                    <div style="text-align: center;"><b><font size="3">LEARNING VIDEOS</font></b></div>
                    <div style="text-align: center;">
                        <font size="3">الفيديو التدريبي</font>
                    </div>
                </div>
            </div>


            <div data-silex-type="text" class="editable-style text-element silex-id-1439554966767-55 nav nav-mark" data-silex-id="silex-id-1439554966767-55" data-silex-href="#!page-how-to-help" style="">
                <div class="silex-element-content normal">
                    <div style="text-align: center;"><b><font size="3">aDDITIONAL FILES</font></b></div>
                    <div style="text-align: center;">
                        <font size="3">ملفات إضافية</font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554966563-53 nav nav-mark" data-silex-id="silex-id-1439554966563-53" data-silex-href="#!page-menu" style="">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">
                        <font size="3"><b>MENU LINK<br>&nbsp;</b></font>
                    </div>
                    <div style="text-align: center;">
                        <font size="3">القائمة المختصرة</font>
                    </div>
                </div>
            </div>

            <div data-silex-type="text" class="editable-style silex-id-1509486793686-1 text-element" data-silex-id="silex-id-1509486793686-1" style="" data-silex-href="#!page-home">
                <div class="silex-element-content normal">
                    <h2 style="text-align: center; height: 0px;" class="heading2">
                        <font color="#ff9900" face="arial, sans-serif" size="6">CHAMPIONS</font>
                    </h2>
                    <div style="text-align: center;">
                        <font color="#ff9900" face="arial, sans-serif" size="5"><br></font>
                    </div>
                    <div style="text-align: center;">
                        <font face="arial, sans-serif" color="#ffffff" size="7">TEAM</font>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490693798023-5 section-element paged-element page-home hide-on-mobile page-content page-efforts" data-silex-id="silex-id-1490693798023-5">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490693798022-4 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490693798022-4">
            <div data-silex-type="container" class="editable-style container-element silex-id-1439554966458-52" data-silex-id="silex-id-1439554966458-52">


















                <div data-silex-type="container" class="editable-style container-element sub-nav silex-id-1439554966357-51 hide-on-mobile" data-silex-href="#!page-content" data-silex-id="silex-id-1439554966357-51">




                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554966255-50" data-silex-href="#!page-home" data-silex-id="silex-id-1439554966255-50">
                        <div class="silex-element-content normal">
                            <p style="height: 0px;" class="normal">
                                <font size="5"><b>Content</b></font>
                            </p>
                            <p style="height: 0px;" class="normal">
                                <font size="5">المحتوى</font>
                            </p>
                            <p></p>
                        </div>
                    </div>
                </div>
                <div data-silex-type="container" class="editable-style container-element sub-nav silex-id-1439554966154-49 hide-on-mobile" data-silex-href="#!page-home" data-silex-id="silex-id-1439554966154-49">




                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554966050-48" data-silex-id="silex-id-1439554966050-48">
                        <div class="silex-element-content normal">
                            <p class="normal"><b style=""><font size="5">The Start</font></b></p>
                            <p class="normal">
                                <font size="5">البداية</font>
                            </p>
                        </div>
                    </div>
                </div>




                <div data-silex-type="container" class="editable-style container-element sub-nav silex-id-1439554965843-46 hide-on-mobile" data-silex-href="#!page-efforts" data-silex-id="silex-id-1439554965843-46">




                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554965740-45" data-silex-href="#!page-home" data-silex-id="silex-id-1439554965740-45">
                        <div class="silex-element-content normal">
                            <p style="height: 0px;" class="normal">
                                <font size="5"><b>Efforts</b><br></font>
                            </p>
                            <p>
                                <font size="5">الجهود</font>
                            </p>
                            <p></p>
                        </div>
                    </div>

                </div>
                <div data-silex-type="container" class="editable-style container-element main-picture paged-element silex-id-1439554965638-44 page-content" data-silex-id="silex-id-1439554965638-44">









                    <div data-silex-type="text" class="editable-style silex-id-1509488264236-2 text-element" data-silex-id="silex-id-1509488264236-2" style="">
                        <div class="silex-element-content normal">
                            <div><b><u>Above menu contains the below Sections:-</u></b></div>
                            <div><b><u><br></u></b></div>
                            <div><b>- EXPLANATION MATERIALS :</b> Materials showing Transactions steps and instructions.</div>
                            <div><b>- LEARNING VIDEOS :</b>&nbsp;important tutorials showing how to pass certain transactions.</div>
                            <div><b>- ADDITIONAL FILES :</b> Files from Previous training sessions, and others ..</div>
                            <div><b>- MENU LINK :</b> this is a link to the menu that contains the most important Options.</div>
                            <div><br></div>
                            <div><br></div>
                            <div style="direction: rtl;"><b><u>تحتوي القائمة المذكورة في الأعلى على التالي :-<br><br></u></b></div>
                            <div style="direction: rtl;"><b>- المستندات التوضيحية : </b>عبارة عن خطوات وشروحات حول القيام ببعض العمليات خطوة بخطوة.</div>
                            <div style="direction: rtl;"><b>- الفيديو التدريبي : </b>وهي دروس بالفيديو تمثل الخطوات أول بأول للقيام ببعض العمليات بشكل توضيحي أكبر.</div>
                            <div style="direction: rtl;"><b>- ملفات إضافية :</b> مستندات خاصة بأبرز الدورات التدريبية ، وغيرها ..</div>
                            <div style="direction: rtl;"><b>- القائمة المختصرة :</b> رابط للقائمة التي تحتوي على أبرز و أهم الخيارات و الأوامر في النظام.</div>
                        </div>
                    </div>
                </div>
                <div data-silex-type="container" class="editable-style container-element main-picture page-home paged-element silex-id-1439554965536-43" data-silex-id="silex-id-1439554965536-43">









                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554964112-29" data-silex-id="silex-id-1439554964112-29" style="">
                        <div class="silex-element-content normal">This Mini-Portal is Created by the Champions Team, we have included most of the important and recommended training&nbsp;and learning materials related to FINACLE.
                            <div><br>
                                <div style="direction: rtl;">تم تأسيس هذه الصفحة من قبل فريق التشامبيونز الخاص بنظام الفيناكل، الهدف الأساسي من هذه الصفحة هو جمع أكبر قدر من المواد التدريبية والتعليمية للنظام.</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div data-silex-type="container" class="editable-style container-element main-picture silex-id-1439554965947-47 paged-element page-efforts" data-silex-id="silex-id-1439554965947-47">











                <div data-silex-type="text" class="editable-style silex-id-1509488761358-3 text-element" data-silex-id="silex-id-1509488761358-3" style="">
                    <div class="silex-element-content normal">
                        <div><b><u><font color="#ffffff">Dear Colleagues ,,,</font></u></b></div>
                        <div>
                            <font color="#ffffff">Going live in FINACLE is a great challenge, and we really do appreciate your hard efforts. We also do understand that all of us need more support specially in particular cases.
                            </font>
                        </div>
                        <div>
                            <font color="#ffffff"><br>
                            </font>
                        </div>
                        <div><u><b><font color="#ffffff">However, calling the support team randomly could cause disorders, so please :-</font></b></u></div>
                        <div>
                            <font color="#ffffff">- 1st, Please contact your Operations Officer or Branch Manager in the Branch.
                            </font>
                        </div>
                        <div>
                            <font color="#ffffff">- 2nd, if you haven't got the support you need, contact your Area's Support person.
                            </font>
                        </div>
                        <div>
                            <font color="#ffffff">- 3rd, you could also contact the Core Support team for any further issues.</font>
                        </div>
                    </div>
                </div>
                <div data-silex-type="text" class="editable-style silex-id-1509488811707-4 text-element" data-silex-id="silex-id-1509488811707-4" style="">
                    <div class="silex-element-content normal">
                        <div style="direction: rtl;"><b><u><font color="#ffffff">الزملاء الأعزاء ،،،</font></u></b></div>
                        <div style="direction: rtl;">
                            <font color="#ffffff">الدخول في مرحلة التطبيق الجديد لنظام الفينكل يعتبر تحدٍ شاق، ونحن نثمن كافة الجهود المبذولة من قبلكم بهذا الأمر. نحن نتفهم كذلك بأننا جميعاً نحتاج للدعم الإضافي في كثير من الأحيان.
                            </font>
                        </div>
                        <div style="direction: rtl;">
                            <font color="#ffffff"><br>
                            </font>
                        </div>
                        <div style="direction: rtl;"><b><u><font color="#ffffff">مع ذلك، فإن الإتصال على أعضاء فرق الدعم بشكل عشوائي قد يتسبب ببعض الإخلال بإجراءات سير المهام، فيرجى :-</font></u></b></div>
                        <div style="direction: rtl;">
                            <font color="#ffffff">- أولا، الرجوع إلى مسئول عمليات الفرع أو مدير الفرع بالمقام الأول.
                            </font>
                        </div>
                        <div style="direction: rtl;">
                            <font color="#ffffff">- ثانياً، في حال عدم التمكن من الحصول على المساعدة المطلوبة، يجب الرجوع إلى مسؤول الدعم في منطقة فرعك.
                            </font>
                        </div>
                        <div style="direction: rtl;">
                            <font color="#ffffff">- ثالثاً، يمكنك أيضاً التواصل مع أعضاء طاقم الدعم (كور سيستم) للأمور الإضافية و المشاكل الأخرى.</font>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490693931165-7 section-element page-home paged-element page-content page-efforts" data-silex-id="silex-id-1490693931165-7">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490693931163-6 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490693931163-6">
            <div data-silex-type="container" class="editable-style container-element white-bg silex-id-1439554965432-42" data-silex-id="silex-id-1439554965432-42">








                <div data-silex-type="container" class="editable-style container-element silex-id-1439554965331-41" data-silex-id="silex-id-1439554965331-41">












                    <div data-silex-type="text" class="editable-style silex-id-1509489030003-5 text-element page-home paged-element page-content page-efforts" data-silex-id="silex-id-1509489030003-5" style="">
                        <div class="silex-element-content normal">
                            <div style="text-align: center;"><b><font color="#ff9900" size="5"><u>Core Team Support</u></font></b></div>
                        </div>
                    </div>



                    <div data-silex-type="image" class="editable-style image-element silex-id-1439554962386-12" data-silex-id="silex-id-1439554962386-12" style=""><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/form_icon_phone.png" class="silex-element-content">
                    </div>
                    <div data-silex-type="text" class="editable-style silex-id-1509489255761-8 text-element" data-silex-id="silex-id-1509489255761-8" style="">
                        <div class="silex-element-content normal">
                            <div>
                                <font color="#000000">- Fatin</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Darine</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Hiyam George</font>
                            </div>
                        </div>
                    </div>
                </div>
                <div data-silex-type="container" class="editable-style container-element silex-id-1439554964925-37" data-silex-id="silex-id-1439554964925-37">









                    <div data-silex-type="text" class="editable-style text-element silex-id-1509489096770-6" data-silex-id="silex-id-1509489096770-6" style="">
                        <div class="silex-element-content normal">
                            <div style="text-align: center;"><b><font color="#ff9900" size="5"><u>Areas' Support</u></font></b></div>
                        </div>
                    </div>
                    <div data-silex-type="text" class="editable-style text-element silex-id-1509489283694-9" data-silex-id="silex-id-1509489283694-9" style="">
                        <div class="silex-element-content normal">
                            <div>
                                <font color="#000000">- Area (A) : Ibrahim Dashti</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Area (B) : **</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Area (C) : Lailah Ahmad</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Area (D) :&nbsp;</font><span style="color: rgb(0, 0, 0);">Fatemah Al-Failakawi</span></div>
                        </div>
                    </div>
                    <div data-silex-type="image" class="editable-style image-element silex-id-1509569771473-0" data-silex-id="silex-id-1509569771473-0" style=""><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/form_icon_phone.png" class="silex-element-content">
                    </div>
                </div>
                <div data-silex-type="container" class="editable-style container-element silex-id-1439554964518-33" data-silex-id="silex-id-1439554964518-33">









                    <div data-silex-type="text" class="editable-style text-element silex-id-1509489102676-7" data-silex-id="silex-id-1509489102676-7" style="">
                        <div class="silex-element-content normal">
                            <div style="text-align: center;"><b><font color="#ff9900" size="5"><u>Champions Team</u></font></b></div>
                        </div>
                    </div>
                    <div data-silex-type="text" class="editable-style text-element silex-id-1509489291973-10" data-silex-id="silex-id-1509489291973-10" style="">
                        <div class="silex-element-content normal">
                            <div>
                                <font color="#000000">- Operations Control: Hussain Akbar</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Head Office: Dhari Abul / Bader Dashti</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Farwaniya: Mariam Sheshtari</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Shuwaikh: Hameed Kazemi</font>
                            </div>
                            <div>
                                <font color="#000000"><br></font>
                            </div>
                            <div>
                                <font color="#000000">- Hawalli: Salman Ali</font>
                            </div>
                        </div>
                    </div>
                    <div data-silex-type="image" class="editable-style image-element silex-id-1509569784167-1" data-silex-id="silex-id-1509569784167-1" style=""><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/form_icon_phone.png" class="silex-element-content">
                    </div>
                </div>
            </div>














        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694152451-11 section-element page-our-mission paged-element" data-silex-id="silex-id-1490694152451-11">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694152449-10 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694152449-10">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961635-5" data-silex-id="silex-id-1439554961635-5">
                <div class="silex-element-content normal">
                    <h1 class="heading1">Our Mission</h1>
                    <p class="normal">Salami do in est, chuck reprehenderit irure porchetta cillum. Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta salami nulla porchetta ground round laboris id. Hamburger exercitation frankfurter, eiusmod nostrud
                        cow ham drumstick strip steak minim picanha quis. Beef ex turkey eu nostrud meatball laboris.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490701849669-19 section-element page-our-mission paged-element" data-silex-id="silex-id-1490701849669-19">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490701849668-18 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490701849668-18"></div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694237194-15 section-element page-how-to-help paged-element" data-silex-id="silex-id-1490694237194-15">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694237193-14 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694237193-14">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961331-2" data-silex-id="silex-id-1439554961331-2">
                <div class="silex-element-content normal">
                    <h1 class="heading1">How to Help</h1>
                    <p class="normal">Salami do in est, chuck reprehenderit irure porchetta cillum. Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta salami nulla porchetta ground round laboris id. Hamburger exercitation frankfurter, eiusmod nostrud
                        cow ham drumstick strip steak minim picanha quis. Beef ex turkey eu nostrud meatball laboris.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490701944668-23 section-element page-how-to-help paged-element" data-silex-id="silex-id-1490701944668-23">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490701944667-22 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490701944667-22"></div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694258064-17 section-element page-contact paged-element" data-silex-id="silex-id-1490694258064-17">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694258062-16 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694258062-16">

            <div data-silex-type="html" class="editable-style silex-id-1492776401689-1 html-element silex-component silex-component-form silex-use-height-not-minheight" data-silex-id="silex-id-1492776401689-1">
                <div class="silex-element-content">
                    <form id="id_1492776633023_506" action="https://formspree.io/your@email.com" method="POST">


                        <div>

                            <input type="text" required="" id="field2" name="field2" placeholder="your@email.com">
                        </div>


                        <div>

                            <textarea required="" id="field3" name="field3" placeholder="Your Message"></textarea>
                        </div>

                        <input type="submit" value="Send">
                    </form>
                    <style>
                        #id_1492776633023_506 input[type=text],
                        select {
                            width: 100%;
                            padding: 12px 20px;
                            margin: 8px 0;
                            display: inline-block;
                            border: 1px solid #ccc;
                            border-radius: 3px;
                            box-sizing: border-box;
                        }
                        
                        #id_1492776633023_506 input[type=submit] {
                            width: 100%;
                            background-color: #4CAF50;
                            color: #FFFFFF;
                            padding: 14px 20px;
                            margin: 8px 0;
                            border: 1px solid #4CAF50;
                            border-radius: 3px;
                            cursor: pointer;
                        }
                        
                        #id_1492776633023_506 textarea {
                            width: 100%;
                            height: 150px;
                            padding: 12px 20px;
                            box-sizing: border-box;
                            border: 2px solid #ccc;
                            border-radius: 3px;
                            background-color: #f8f8f8;
                            font-size: 16px;
                            resize: none;
                        }
                        
                        #id_1492776633023_506 label {
                            color: #000000;
                        }
                        
                        #id_1492776633023_506 {
                            border-radius: 3px;
                            display: flex;
                            flex-direction: column;
                            justify-content: space-between;
                            height: 100%;
                        }
                    </style>

                </div>
            </div>
            <div data-silex-type="html" class="editable-style silex-id-1492776672785-2 html-element silex-component silex-component-map silex-use-height-not-minheight" data-silex-id="silex-id-1492776672785-2">
                <div class="silex-element-content">
                    <div id="mapdiv_1492776672835_337">
                        <div class="ol-viewport" data-view="1928" style="position: relative; overflow: hidden; width: 100%; height: 100%; touch-action: none;"><canvas class="ol-unselectable" style="width: 100%; height: 100%; display: none;"></canvas>
                            <div class="ol-overlaycontainer"></div>
                            <div class="ol-overlaycontainer-stopevent">
                                <div class="ol-zoom ol-unselectable ol-control"><button class="ol-zoom-in" type="button" title="Zoom in">+</button><button class="ol-zoom-out" type="button" title="Zoom out">−</button></div>
                                <div class="ol-rotate ol-unselectable ol-control ol-hidden"><button class="ol-rotate-reset" type="button" title="Reset rotation"><span class="ol-compass">⇧</span></button></div>
                                <div class="ol-attribution ol-unselectable ol-control ol-collapsed" style="display: none;">
                                    <ul>
                                        <li style="display: none;"></li>
                                    </ul><button type="button" title="Attributions"><span>i</span></button></div>
                            </div>
                        </div>
                    </div>
                    <style>
                        #mapdiv_1492776672835_337 {
                            width: 100%;
                            height: 100%;
                        }
                    </style>
                    <script>
                        function init_1492776672835_337() {
                            if(!$('body').hasClass('silex-runtime') && typeof(ol) === 'undefined') {
                                // wait for dependencies to be loaded
                                setTimeout(init_1492776672835_337, 100);
                                return;
                            }
                        
                            // apply position and zoom
                            // from map URL //www.openstreetmap.org/#map=18/48.88680/2.34235&layers=C
                            var params = '//www.openstreetmap.org/#map=18/48.87378/2.29489&layers=C'.match(/.*map=([0-9]*)\/(.*)\/(.*)&layers=(.)/);
                            if(params) {
                                var zoom = parseFloat(params[1]);
                                var lat = parseFloat(params[2]);
                                var lon = parseFloat(params[3]);
                                var layer = params[4];
                                var center = ol.proj.fromLonLat([lon, lat]);
                                var map = new ol.Map({
                                  layers: [
                                    new ol.layer.Tile({
                                      source: new ol.source.OSM()
                                    })
                                  ],
                                  target: 'mapdiv_1492776672835_337',
                                  view: new ol.View({
                                    center: center,
                                    zoom: zoom
                                  })
                                });
                                
                                var iconFeature = new ol.Feature({
                                    geometry: new ol.geom.Point(center)
                                });
                                var vectorSource = new ol.source.Vector({
                                    features: [iconFeature]
                                });
                                var vectorLayer = new ol.layer.Vector({
                                    source: vectorSource
                                });
                                var iconStyle = new ol.style.Style({
                                    image: new ol.style.Icon(({
                                        anchor: [0.5, 1],
                                        anchorXUnits: 'fraction',
                                        anchorYUnits: 'fraction',
                                        opacity: 1,
                                        src: 'https://openlayers.org/en/v4.0.1/examples/data/icon.png'
                                    }))
                                });
                                iconFeature.setStyle(iconStyle);
                                map.addLayer(vectorLayer);
                                
                            }
                        }
                        init_1492776672835_337();
                        $(document).on('silex:resize', function() {
                            $('#mapdiv_1492776672835_337').empty();
                            init_1492776672835_337();
                        });
                    </script>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509571589425-15 page-menu paged-element" data-silex-id="silex-id-1509571589425-15">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-container-content container-element prevent-draggable silex-id-1509571589426-16" data-silex-id="silex-id-1509571589426-16">
            <div data-silex-type="container" class="editable-style container-element white-bg silex-id-1509571589426-17 page-menu paged-element" data-silex-id="silex-id-1509571589426-17" style="">











                <div data-silex-type="text" class="editable-style silex-id-1509571705685-30 text-element" data-silex-id="silex-id-1509571705685-30" style="">
                    <div class="silex-element-content normal">
                        <h3 style="height: 0px;">
                            <font size="6" color="#444444" class="heading3"><u>Menu Link - القائمة المختصرة</u></font>
                        </h3>
                        <div>
                            <font size="6" color="#444444" class="heading3"><br></font>
                        </div>
                        <p></p>
                    </div>
                </div>
            </div>














        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1509729107864-36 section-element page-menu paged-element" data-silex-id="silex-id-1509729107864-36">
        <div data-silex-type="container" class="editable-style silex-id-1509729107864-35 container-element silex-element-content silex-container-content website-width prevent-draggable" data-silex-id="silex-id-1509729107864-35">
            <div data-silex-type="text" class="editable-style text-element silex-id-1509730790091-43" data-silex-id="silex-id-1509730790091-43" style="">
                <div class="silex-element-content normal">
                    <div>
                        <font color="#000000"><b>- The Shortcuts Menu is one of the most helpful things that could support you to invoke the required Option in "Core".</b></font>
                    </div>
                    <div>
                        <font color="#000000"><b>- Keep the Link of the menu opened on the side all time While working on Finacle (see below screen).</b></font>
                    </div>
                    <div>
                        <font color="#000000"><b>- keep it saved in your "Favorites" or "your Desktop" for an easier Access.</b></font>
                    </div>
                    <div>
                        <font color="#000000"><br></font>
                    </div>
                    <div>
                        <font color="#000000"><br></font>
                    </div>
                    <div style="direction: rtl;">
                        <font color="#000000" style=""><b style="">- القائمة المختصرة هي واحدة من أكثرالأمور التي ستساعدك للحصول على الأوامر المطلوبة في "نظام الكور".</b></font>
                    </div>
                    <div style="direction: rtl;">
                        <font color="#000000" style=""><b style="">- ابق صفحة القائمة مفتوحة دائماً طوال الوقت على الجانب بمتصفح مستقل (شاهد المثال بالصورة أدناه).</b></font>
                    </div>
                    <div style="direction: rtl;">
                        <font color="#000000" style=""><b style="">- قم بإضافة الصفحة إلى "المفضلة Favorits" أو قم بتخزينها على "سطح المكتب Desktop".</b></font>
                    </div>
                </div>
            </div>
            <div data-silex-type="image" class="editable-style silex-id-1509732400668-47 image-element" data-silex-id="silex-id-1509732400668-47" style=""><img src="content_bg.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style silex-id-1509732506568-48 text-element" data-silex-id="silex-id-1509732506568-48" style="">
                <div class="silex-element-content normal">
                    <div style="text-align: center;"><b style="color: rgb(0, 0, 0);">Example of how to keep the Menu on the side - مثال لشكل القائمة وهي مبقية على جانب الشاشة</b></div>
                </div>
            </div>
            <div data-silex-type="html" class="editable-style silex-id-1509773825344-49 html-element" data-silex-id="silex-id-1509773825344-49" style="">
                <div class="silex-element-content"><a href="//www.google.com" target="_blank">Click Here to Open the Shortcuts Menu page - اضغط هنا لفتح صفحة القائمة المختصرة</a></div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1509730767790-42 section-element page-menu paged-element" data-silex-id="silex-id-1509730767790-42">
        <div data-silex-type="container" class="editable-style silex-id-1509730767789-41 container-element silex-element-content silex-container-content website-width prevent-draggable" data-silex-id="silex-id-1509730767789-41"></div>

    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1509775843632-83 section-element page-learning-videos paged-element" data-silex-id="silex-id-1509775843632-83">
        <div data-silex-type="container" class="editable-style silex-id-1509775843631-82 container-element silex-element-content silex-container-content website-width prevent-draggable" data-silex-id="silex-id-1509775843631-82">
            <div data-silex-type="container" class="editable-style container-element white-bg silex-id-1509775896415-84 page-learning-videos paged-element" data-silex-id="silex-id-1509775896415-84" style="">












                <div data-silex-type="text" class="editable-style text-element silex-id-1509776686937-87" data-silex-id="silex-id-1509776686937-87" style="">
                    <div class="silex-element-content normal">
                        <h3 style="height: 0px;">
                            <font size="6" color="#444444" class="heading3"><u>Learning Videos - الفيديو التدريبي</u></font>
                        </h3>
                        <div>
                            <font size="6" color="#444444" class="heading3"><u><br></u></font>
                        </div>
                        <div>
                        </div>
                        <p></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509774845491-57 page-learning-videos paged-element" data-silex-id="silex-id-1509774845491-57">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509774845491-58" data-silex-id="silex-id-1509774845491-58">




            <div data-silex-type="image" class="editable-style image-element silex-id-1509774845492-60 page-learning-videos paged-element" data-silex-id="silex-id-1509774845492-60" style=""><img src="content_bg.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1509774998149-67 page-learning-videos paged-element" data-silex-id="silex-id-1509774998149-67" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl; text-align: center;"><b style="font-size: large; color: rgb(0, 0, 0);">فتح ملف عميل شخصي -&nbsp;</b>
                        <font size="4">
                            <font color="#000000" style=""><b style="">Open CIF for a Person</b></font><b style="color: rgb(0, 0, 0);">&nbsp;</b></font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1509774845492-59 page-learning-videos paged-element" data-silex-id="silex-id-1509774845492-59" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u><br></u></b></span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u>الوصف</u></b></span><b style="color: rgb(0, 0, 0);">: </b><span style="color: rgb(0, 0, 0);">فتح ملف عميل CIF شخصي (لفتح حساب شخصي)</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>المدة</u>: </b><span style="color: rgb(0, 0, 0);">8 دقائق</span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b><u>النظام</u></b>: CRM</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>الملاحظات</u>: </b><span style="color: rgb(0, 0, 0);">يمكن استخدامه للحسابات الشخصية</span></div>
                </div>
            </div>

            <div data-silex-type="html" class="editable-style html-element silex-id-1509774845492-62" data-silex-id="silex-id-1509774845492-62" style="">
                <div class="silex-element-content"><a href="//www.google.com" target="_blank">Click Here to Open - اضغط هنا لفتح الفيديو</a></div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509774845497-63 page-learning-videos paged-element" data-silex-id="silex-id-1509774845497-63">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509774845497-64" data-silex-id="silex-id-1509774845497-64"></div>

    </div>












    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509776784490-88 page-learning-videos paged-element" data-silex-id="silex-id-1509776784490-88">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509776784491-89" data-silex-id="silex-id-1509776784491-89">




            <div data-silex-type="image" class="editable-style image-element page-learning-videos paged-element silex-id-1509776784491-90" data-silex-id="silex-id-1509776784491-90" style=""><img src="content_bg.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element page-learning-videos paged-element silex-id-1509776784492-91" data-silex-id="silex-id-1509776784492-91" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl; text-align: center;"><b style="font-size: large; color: rgb(0, 0, 0);">فتح ملف عميل CIF لشركة ذ.م.م -&nbsp;</b>
                        <font size="4">
                            <font color="#000000" style=""><b style="">Open CIF for LTD Company</b></font><b style="color: rgb(0, 0, 0);">&nbsp;</b></font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element page-learning-videos paged-element silex-id-1509776784492-92" data-silex-id="silex-id-1509776784492-92" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u><br></u></b></span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u>الوصف</u></b></span><b style="color: rgb(0, 0, 0);">: </b><span style="color: rgb(0, 0, 0);">فتح ملف عميل CIF لشركة ذات مسئولية محدودة</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>المدة</u>: </b><span style="color: rgb(0, 0, 0);">8 دقائق</span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b>النظام</b>: CRM</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>الملاحظات</u>: </b><span style="color: rgb(0, 0, 0);">يمكن استخدامه للمؤسسات/الشركات بشرط تغيير نوع الكيان.</span></div>
                </div>
            </div>

            <div data-silex-type="html" class="editable-style html-element silex-id-1509776784492-93" data-silex-id="silex-id-1509776784492-93" style="">
                <div class="silex-element-content"><a href="//www.google.com" target="_blank">Click Here to Open - اضغط هنا لفتح الفيديو</a></div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509777005257-94 page-learning-videos paged-element" data-silex-id="silex-id-1509777005257-94">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509777005257-95" data-silex-id="silex-id-1509777005257-95"></div>

    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509777011264-96 page-learning-videos paged-element" data-silex-id="silex-id-1509777011264-96">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509777011264-97" data-silex-id="silex-id-1509777011264-97">




            <div data-silex-type="image" class="editable-style image-element page-learning-videos paged-element silex-id-1509777011264-98" data-silex-id="silex-id-1509777011264-98" style=""><img src="content_bg.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element page-learning-videos paged-element silex-id-1509777011265-99" data-silex-id="silex-id-1509777011265-99" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl; text-align: center;"><b style="font-size: large; color: rgb(0, 0, 0);">فتح حساب جاري أو توفير للعميل - Open Current or Savings account</b></div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element page-learning-videos paged-element silex-id-1509777011265-100" data-silex-id="silex-id-1509777011265-100" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u><br></u></b></span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u>الوصف</u></b></span><b style="color: rgb(0, 0, 0);">: </b><span style="color: rgb(0, 0, 0);">فتح حساب جاري أو توفير لعميل تم فتح CIF له مسبقاً.</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>المدة</u>: </b><span style="color: rgb(0, 0, 0);">8 دقائق</span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b><u>النظام</u></b>: Core</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>الملاحظات</u>: </b><span style="color: rgb(0, 0, 0);">يستخدم للأفراد و الكيانات.</span></div>
                </div>
            </div>

            <div data-silex-type="html" class="editable-style html-element silex-id-1509777011266-101" data-silex-id="silex-id-1509777011266-101" style="">
                <div class="silex-element-content"><a href="//www.google.com" target="_blank">Click Here to Open - اضغط هنا لفتح الفيديو</a></div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509778750982-102 page-learning-videos paged-element" data-silex-id="silex-id-1509778750982-102">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509778750982-103" data-silex-id="silex-id-1509778750982-103"></div>

    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509778754240-104 page-learning-videos paged-element" data-silex-id="silex-id-1509778754240-104">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509778754241-105" data-silex-id="silex-id-1509778754241-105">




            <div data-silex-type="image" class="editable-style image-element page-learning-videos paged-element silex-id-1509778754241-106" data-silex-id="silex-id-1509778754241-106" style=""><img src="content_bg.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element page-learning-videos paged-element silex-id-1509778754241-107" data-silex-id="silex-id-1509778754241-107" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl; text-align: center;">
                        <font color="#000000" size="4"><b>فتح حساب وديعة - Open a Term Deposit Ac</b></font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element page-learning-videos paged-element silex-id-1509778754242-108" data-silex-id="silex-id-1509778754242-108" style="">
                <div class="silex-element-content normal">
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u><br></u></b></span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b style=""><u>الوصف</u></b></span><b style="color: rgb(0, 0, 0);">: </b><span style="color: rgb(0, 0, 0);">فتح حساب وديعة لعميل تم فتح CIF له مسبقاً.</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>المدة</u>: </b><span style="color: rgb(0, 0, 0);">8 دقائق</span></div>
                    <div style="direction: rtl;"><span style="color: rgb(0, 0, 0);"><b><u>النظام</u></b>: Core</span></div>
                    <div style="direction: rtl;"><b style="color: rgb(0, 0, 0);"><u>الملاحظات</u>: </b><span style="color: rgb(0, 0, 0);">يستخدم للأفراد و الكيانات.</span></div>
                </div>
            </div>

            <div data-silex-type="html" class="editable-style html-element silex-id-1509778754242-109" data-silex-id="silex-id-1509778754242-109" style="">
                <div class="silex-element-content"><a href="//www.google.com" target="_blank">Click Here to Open - اضغط هنا لفتح الفيديو</a></div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style section-element silex-id-1509778854467-110 page-learning-videos paged-element" data-silex-id="silex-id-1509778854467-110">
        <div data-silex-type="container" class="editable-style container-element silex-element-content silex-container-content website-width prevent-draggable silex-id-1509778854468-111" data-silex-id="silex-id-1509778854468-111"></div>

    </div>
</body>

</html>