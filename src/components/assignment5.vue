<template>
  <div>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

   <div class="header">
      <div class="header-left">
        <i class="fa fa-cloud header-left-icon" style="color:lightblue;"></i>
        <label calss="header-left-icon">FUSE</label>
        <button id="btn1">React</button>
        <i class="fa fa-bars header-left-icon"></i>
      </div>
      <div class="header-right">
        <i class="fa header-right-icon">&#xf133;</i>
        <i class="fa header-right-icon">&#xf0e0;</i>
        <i class="fa header-right-icon">&#xf007;</i>
        <b class="header-right-icon">A</b>
         <i class="fa fa-star header-right-icon" style="color:#f1c40f"></i>
         <div style="float: right;">
            <div style="display:inline;"><i class="fa fa-user-circle fa-2x user"></i>
            </div>
            <div class="username">
               <label id="name"><b>Devanand</b></label>
               <br>
               <label id="role">Guest</label>
            </div>
            <i class="fa fa-angle-down angle2"></i>
            <button class="btn2">
               <i class="fa fa-search"></i></button>
            <i class="fa fa-list-ul list"></i>
         </div>
      </div>
   </div>
   <div class="menu">
      <ol type="">
         <div class="menu-sub">
         <label style="color: #c8c2c2;">Applications</label>
      </div>
         <div class="menu-sub">
            <i class="fa fa-th-large"></i>
            <label class="text">Dashboard</label>
            <i class="fa fa-angle-down angle"></i>
         </div>
         <div class="menu-sub">
            <i class="fa fa-calendar-o"></i>
            <label class="text">Calender</label>
         </div> 
         <div class="menu-sub">
            <i class="fa fa-envelope"></i>
            <label class="text">Mail</label>
            <div id="notification1">25</div>
         </div>
         <div class="menu-sub">
            <i class="fa fa-folder"></i>
            <label class="text">File Manager</label>
         </div>
         <div class="menu-sub">
            <i class="fa fa-address-book"></i>
            <label class="text">Contacts</label>
         </div>
         <div class="menu-sub">
          <label style="color: #c8c2c2;">Pages</label>
       </div>
         <div class="menu-sub">
            <i class="fa fa-lock"></i>
            <label class="text">Authentication</label>
          <div style="float:right; "> <div id="notification2">10</div>
         <i class="fa fa-angle-down angle angle-menu"></i>
      </div>
         </div>
         <div class="menu-sub">
            <i class="fa fa-clock-o"></i>
         <label class="text">Coming soon</label>
         </div>
         <div class="menu-sub">
            <i class="fa fa-exclamation-circle"></i>
            <label class="text">Errors</label>
            <i class="fa fa-angle-down angle"></i>
         </div>
         <div class="menu-sub">
            <i class="fa fa-file-text-o"></i>
            <label class="text">Invoice</label>
            <i class="fa fa-angle-down angle"></i>
         </div>
         <div class="menu-sub">
            <i class="fa fa-wrench"></i>
            <label class="text">Maintenance</label>
         </div>
         <div class="menu-sub">
            <i class="fa fa-dollar"></i>
            <label class="text">Pricing</label>
            <i class="fa fa-angle-down angle" style=";"></i>
         </div>
         <div class="menu-sub">
            <i class="fa fa-user"></i>
            <label class="text">Profile</label>
         </div>
         <div class="menu-sub">
            <i class="fa fa-search"></i>
            <label class="text">Search</label>
            <i class="fa fa-angle-down angle"></i>
         </div>
         <div class="menu-sub">
            <i class="fa fa-question-circle"></i>
            <label class="text">Faq</label>
         </div>
         <div class="menu-sub">
            <i class="fa fa-book"></i>
            <label class="text">Knowledge Base</label>
         </div>
         <div class="menu-sub">
         <label style="color: #c8c2c2;">User Interface</label>
      </div>
         <div class="menu-sub">
            <i class="fa fa-area-chart"></i>
            <label class="text">Icons</label>
         </div>
         </ol>
   </div>
   <div class="top">
      <div class="top-left">
             <i class="fa fa-bars top-icon"s></i>
             <i class="fa fa-search top-icon top-icon-right"></i> 
             <br><br>
             <label id="top-body"><b>My Files&nbsp;<i class="fa fa-angle-right"></i>&nbsp;Documents</b></label> 
             <div class="circle"><label id="circle-name">+</label></div>
        </div>
      <div class="top-right">
            <i class="fa fa-trash-o trash"></i>
            <i class="fa fa-download top-right-icon"></i>
            <i class="fa fa-ellipsis-v top-right-icon"></i>
            <br><br>
            <label style="color:white;font-size:14px;">Work Documents</label> 
            <br> 
            <label style="color:#ecf0f1;font-size:10px;">Edited: April 27, 2018</label>  
            <div id="settings"><i class="fa fa-gear gear-icon"></i></div>
        </div>
   </div>
   <div class="middle">
       <div class="middle-left">
             <table>
                <col width="60"> <col width="170"> <col width="100"> <col width="100"> <col width="90"> <col width="100">
                <tr><th></th><th>Name</th><th>Type</th><th>Owner</th><th>Size</th><th>Modified</th>
                </tr>
                <tr ><td><i class="fa fa-folder file file-sub1"></i></td><td>Work Documents</td><td>folder</td><td>me</td><td>&nbsp;&nbsp;&nbsp;-</td><td>April 27,2018</td>
                </tr>
                <tr><td><i class="fa fa-folder file file-sub1"></i></td><td>Public Documents</td><td>folder</td><td>public</td><td>&nbsp;&nbsp;&nbsp;-</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-folder file file-sub1"></i></td><td>Private Documents</td><td>folder</td><td>me</td><td>&nbsp;&nbsp;&nbsp;-</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Ongoing Projects</td><td>document</td><td>Emily Bennett</td><td>1.2 Mb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Ongoing Projects</td><td>document</td><td>Emily Bennett</td><td>980 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file-image-o file file-sub2"></i></td><td>Invoices</td><td>spreadsheet</td><td>Emily Bennett</td><td>750 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Crash Logs</td><td>document</td><td>Emily Bennett</td><td>980 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>System Logs</td><td>document</td><td>Emily Bennett</td><td>52 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file-image-o file file-sub2"></i></td><td>Prices</td><td>spreadsheet</td><td>Emily Bennett</td><td>27 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Anabelle Manual</td><td>document</td><td>Emily Bennett</td><td>1.1 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file-image-o file file-sub2"></i></td><td>Stream Summer Sale Budget</td><td>spreadsheet</td><td>Emily Bennett</td><td>505 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-folder file file-sub1"></i></td><td>Public Documents</td><td>folder</td><td>public</td><td>&nbsp;&nbsp;&nbsp;-</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-folder file file-sub1"></i></td><td>Private Documents</td><td>folder</td><td>me</td><td>&nbsp;&nbsp;&nbsp;-</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Ongoing Projects</td><td>document</td><td>Emily Bennett</td><td>1.2 Mb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Ongoing Projects</td><td>document</td><td>Emily Bennett</td><td>980 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file-image-o file file-sub2"></i></td><td>Invoices</td><td>spreadsheet</td><td>Emily Bennett</td><td>750 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Crash Logs</td><td>document</td><td>Emily Bennett</td><td>980 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>System Logs</td><td>document</td><td>Emily Bennett</td><td>52 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file-image-o file file-sub2"></i></td><td>Prices</td><td>spreadsheet</td><td>Emily Bennett</td><td>27 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file file file-sub3"></i></td><td>Anabelle Manual</td><td>document</td><td>Emily Bennett</td><td>1.1 Kb</td><td>April 27, 2018</td>
                </tr>
                <tr><td><i class="fa fa-file-image-o file file-sub2"></i></td><td>Stream Summer Sale Budget</td><td>spreadsheet</td><td>Emily Bennett</td><td>505 Kb</td><td>April 27, 2018</td>
                </tr>
             </table> 
         </div>
       <div class="middle-right">
          <i class="fa fa-folder fa-3x folder"></i>
          <br>
          <i class="fa fa-toggle-on" style="font-size:20px;color: #85c9e1;"></i>
          <label style="font-size:13px;">&nbsp;Available Office</label><br><br><br>
          <label><b>Info</b></label><br><br><br>
          <label ><b>Type</b></label>
          <label style="padding-left: 40px;">folder</label><br><br><br>
          <label><b>Size</b></label>
          <label style="padding-left: 49px;">-</label><br><br><br>
          <label><b>Location</b></label>
          <label style="padding-left: 17px;">My Files <i class="fa fa-angle-right" style="font-size:15px"></i> Documents</label><br><br><br>
          <label><b>Owner</b></label>
          <label style="padding-left: 30px;">me</label><br><br><br>
          <label><b>Modifoed</b></label>
          <label style="padding-left: 15px;">April 27, 2018</label><br><br><br>
          <label><b>Opened</b></label>
          <label style="padding-left: 25px;">April 27, 2018</label>
         </div>
   </div>
   <div class="footer">
        <button class="btn3">
         <i class="fa fa-cart-plus"></i> Purchage Fuse React</button>
        <div class="footer-right">
        <i class="fa fa-database footer-right"></i>
        <i class="fa fa-flag-checkered footer-right"></i>
        <i class="fa fa-comments-o footer-right"></i>
        <i class="fa fa-battery-3 footer-right"></i>
     </div>
   </div>
  </div>
</template>

<script>
export default {
  name: 'assignment5',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App assignment5'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
*{
         margin:0;
         padding: 0;
         font-family: Arial;
      }
    .header{
            height: 40px;
            position: relative;
            display: flex;
            }
         .header-left{ 
          width:200px;
          height: 40px;
          background-color: #2f2e2e;
          position: absolute;
          display: inline;
          color: white;
           }
           #btn1{
            background-color: #05114b;
            height:20px;width:40px;
            border-radius: 2px;
             color: dodgerblue;
            border:none;
           }
         .header-right{
          height: 40px;
          width: 1055px;
          margin-left: 200px;
          background-color: #ffffff;
         }
         .header-right-icon{
          font-size: 20px;
          padding-left: 15px;
          padding-top: 12px;
         }  
         .btn2{
          width:65px;
          height: 40px;
          margin-left:5px;
           background-color: white;
           border: none;
           border-left:1px solid gray;
           border-right: 1px solid gray;
           display: inline;
           font-size: 20px;
         }
         .menu{
          width:200px;
          height: 650px;
          background-color: #3d3d3d;
          float: left;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.5);
            color:#f0f2fa; 
            font-size: 13px;
            display: flex;
            
         }
         .menu-sub{
            width: 180px;
            height: 24px;
            border:none;
            padding-left: 20px;
            padding-top: 10px;
            font-size: 12px;
         }
         .menu-sub:hover{ 
            background-color: #5dade2;
            font-size: 14px;
            color: #f7efee;
          }
         .top{
          height:100px;
            background-color: #363434;
          margin-left: 200px;
         }
         .top-left{
          width: 860px;
          height: 100px;
          background-color: #626161;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            float:left;
          
         }
         .top-right{
            width:230px;
            height:100px;
             background-color: #363434 ;
             float: right;
         }
         .middle{
          height: 500px;
          border-top: none;
          margin-left: 200px;
         }
         .circle{
            width: 35px;
            height:35px;
            border: 1px solid dodgerblue;
            border-radius: 50px;
            background-color: dodgerblue;
            margin-top: -8px;
            overflow: fixed;
            margin-left: 20px;
            margin-top: 10px;
         }
         .circle #circle-name{
          color: white; 
          font-size: 27px;
          margin-left:10px;
          margin-top:3px;
          position:fixed;
         }
         .middle-left{ 
          
            width: 860px;
            height: 500px; 
            box-shadow: 0 5px 8px 0 rgba(0, 0, 0, 0.1), 0 6px 20px 0 rgba(0, 0, 0, 0.1);
            float: left;
            overflow: scroll;
         }
         ::-webkit-scrollbar{
          width: 0px;
          color:transparent;
         }
         table {

         border-collapse:collapse;
         width: 100%;
         font-size: 12px;
         overflow: scroll;
           }
           tr:hover{ background-color: #dddbdd; }

        td, th {
          border-bottom: 1px solid #dddddd;
          text-align: left;
          padding: 10px;

            }
            tr{ font-weight: 540; }
         .middle-right{
            width:230px;
            height:500px;
            float:right;
            margin-left:-15px;
            font-size: 12px;
            padding-left: -15px;
         }
         .footer{
          background-color: #373233;
          height: 50px;
         }
         .footer-right{
          float: right;
          padding-top: 5px;
          padding-right: 15px;
          color: white; font-size: 20px; padding-right: 15px;
         }
        .header-left-icon{
          font-size: 16px;
          padding-top: 10px;
          text-shadow:2px 2px 4px #000000;
          padding-left: 10px;
          padding-right: 15px;
          padding-top: 15px;
        }
        .angle{
          font-size:13px;
          float:right;
          margin-right: 20px;
        }
        .angle2{
          font-size:20px;
          display: inline;
        }
        .text{
          display:inline;
          padding-left:10px;
        }
        .file{
          font-size: 18px; 
          padding-left: 15px;
        }
        .file-sub1{color:#f1c40f;}
        .file-sub2{color:green;}
        .file-sub3{color:blue;}
        .folder{
          font-size:40px;
          color:#f1c40f;
          margin-left:85px;
          margin-top: 60px;
          margin-bottom:70px;
        }
        .user{
          padding-top:5px;
          float:left;
          width:30px;
        }
        .username{
        width: 90px;
          height:40px;
          float:left;
          display: inline;}
        .username #name{font-size:16px;
          display:inline;
          vertical-align: top;
          float:top;
          padding-left:5px;
          color: #373233;position: absolute;
          margin-top:5px; 
        }
        .username #role{
          color: #8f9b9e;
          font-size:14px;
          padding-left:8px;
        }
        .list{
          font-size:20px; margin-left: 15px;margin-right: -40px;
        }
        .lbl-space{
          padding-left: 10px;
        }
        .btn3{
          margin-left: 15px;
          margin-top:10px;
          border-radius: 3px; 
          background-color: dodgerblue;
           border: none; 
           height: 25px;
           color: white;
           width:160px;
        }
        .top-icon{
          color:white;padding-top: 15px;padding-right: 15px;
          padding-left: 20px;
        }
        .top-icon-right{
          float:right;
        }
        #top-body{
          color:white;font-size: 18px;padding-left: 50px;
        }
        #notification1{
          width:15px;height: 13px;font-size: 10px; color: white;float: right;border-radius:5px;padding-left:2px; background-color: red;margin-right: 10px;
        }
        #notification2{
          width:15px;height: 13px;font-size: 10px;background-color: #a5132d; color: white;float:;border-radius:5px;padding-left:2px;margin-right: 30px;
        }
        .angle-menu{
          margin-left: 20px;position: absolute;margin-top: -13px;
        }
        .trash{
          font-size:20px;color: white;padding-left: 120px; padding-top: 15px;
        }
        .top-right-icon{
          font-size:20px; color:white;padding-left:  15px;
        }
        #settings{
          float: right;width: 28px;height: 30px;padding-right:10px;margin-right:4px;margin-top: -10px;border-radius: 3px;
        }
        .gear-icon{font-size:25px;color: white;padding-left: 10px;padding-top: 4px;}
</style>
