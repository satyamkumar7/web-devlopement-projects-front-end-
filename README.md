# web-devlopement-projects-front-end-
In this we are going through the web devlopement  projects hand made by me .It is very simple and understandable by eveyone.

SIMPLE SWIGGY PROJETCS:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swiggy-The online food delivery app</title>
    <style>
      #nav{
          margin: 6px 8px;
          padding: 15px 10px;
          border: 2px solid blueviolet;
          background-color: burlywood;
          list-style-type: none;
          border-radius: 6px;
      }
      #nav a{
         text-decoration: none;
         color: white;
         margin: 5px 23px;
          padding: 7px 8px;
      }
     #nav a:hover{
           background-color: cadetblue;
      }
      .active{
          background-color: rgb(49, 40, 180);
      }
      
      .search{
          padding: 0px 0px;
          float: right;
      }
      img{
          width:20%
      }
      h2{
          color: darkred;
      }
      .heading h1{
          color: firebrick;
         
      }
      .login a{
          float: right;
          margin: 1px 12px;
          padding: 10px 29px;
          text-decoration: none;
          font-size: 30px;
          border: 2px solid palevioletred;
      }
      .login a:hover{
          background-color: peru;
          color: royalblue;
      }
      .submit :hover{
            background-color: red;
            cursor: pointer;
      }
      #former{
          color: seagreen;
      }
      .center{
          background-color: steelblue;
          text-align: center;
          color: turquoise;
      }
      .center img{
          width: 1%;
          float: right;
          margin: 2px -2px;
          padding: 4px 4px;
      }
    
    </style>
    <div class="login">
        <a href="#">Log-in</a>
        <a href="#">Sign-up</a> <br><br>
    </div>
      <div class="heading">
      <h1>Welcome to Swiggy</h1>
</div>
    <div id="nav" class="navigation">
        <a href="#" class="active">Home</a> 
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact us</a> 
        <a href="#">Mail us</a>  
        <div class="search">
            <input type="search" name="searchbox" placeholder="Search the food item">
        </div>
    </div>
    <h2>Here is some of the top picks for you</h2>
    <img src="https://images.pexels.com/photos/315755/pexels-photo-315755.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Error loading image">
    <img src="https://images.pexels.com/photos/1633578/pexels-photo-1633578.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Error loading image">
    <img src="https://images.pexels.com/photos/1460872/pexels-photo-1460872.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="Error loading image">
    <img src="https://images.pexels.com/photos/769969/pexels-photo-769969.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="Error loading image">
    <h3>You need to fill this form to get the product at your doorstep</h3>
    <form action="get.php">
    <div class="form" id="former">
       Name: <input type="text" name="enter your name"><br><br>
       Address: <input type="text" name="enter your address"><br><br>
      Mobile number: <input type="number" name="enter your mobile number" ><br><br>
      <p>Please select your gender:</p>
      <input type="radio" id="male" name="gender" value="male">
      <label for="male">Male</label><br>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label><br>
      <input type="radio" id="other" name="gender" value="other">
      <label for="other">Other</label>
      <label for="foods">Choose the type of food you want: </label>
      <select name="foods" id="foods">
          <option value="Breakfast item">Breakfast item</option>
          <option value="Lunch item">Lunch item</option>
          <option value="Rough Dinner item">Rough Dinner item</option>
          <option value="Dinner item">Dinner item</option>
          <br><br>
         
      </select><br><br>
    </form>
     
    </div>
    <div class="submit">
        <input type="submit" value="Submit Now"><hr>
    </div>
    <footer>
        <div class="center">
            Copyright &copy; www.myOnlineMeal.com. All rights reserved!
            <img src="https://png.pngtree.com/element_our/md/20180626/md_5b321ca3631b8.jpg" alt="Error Loading image">
            <img src="https://1000logos.net/wp-content/uploads/2016/11/Facebook-logo-500x350.png" alt="Error Loading image">
            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASwAAACoCAMAAABt9SM9AAAAeFBMVEX///8AovMAnfIAmvLI5Pu33PoAoPMAnPMAnPQAmvQAn/QAoPLr9vz4/P0cpvM9rvJYtvQrqfKXzvbX7Pr0+vxyv/a93/tOsvLP6Pn0+/zk8vtvv/Sm1fjB4fgAlfKBxfWRy/Z+w/Zmu/SPy/Oe0far1/be7/uKyfhIspxeAAAIPklEQVR4nO2da2OyIBTHAw0UzEuX5bZ6ukzr+3/DJ9vWykRBVA6b/3drLeg3wAPncM5kMmqUBTplx4RRDECUhfF8YZpHjaYhZYQjIOKE0XBjmolAi5CCAfUtjpFrmkuV5j44VIW4vzNN5lkrahqLSDg2zaasHVhWF1pH03Qe9eKYJlInCmqZnwEeV4WcwDShOx2YaRz1YoAm4hL0JCzkwxlaG+AD6zK09qYZ3RQR0zCaxBPTjG4CvrwXcpamIX3pZAEsmpqm9CXXAlj4xTSlL7nYNIpm4alpSl8aYSlohKWgEZaCRlgKGmEpaISloBGWggaCRRimHuWcE8ejTHE7+qdgEeyv99u32WeLQZqvuMcUPCR/CBbzj9unZk97VON7I4/HRn8GFmPzWXXL28irxsX9OH+g9UdgETqvaTtNKhonXpJOVg+rGmxYXR2eenHDSdSmPBeJF7mTyevjUTdoWOyjE1qcNn/JILlrimO6uoaD7O1Zs3gy2fr6rAh6k+nA+9eBGmd+tHn9fK3UJ8iw6OXhlWnTYolgYS/rw7+Aon6U3diWBhZkWDwsXt95mqwi6S7k/5Ld9vXn56D8jwIMC2fXX7xrnTcTFY9MaQg++ZsAw/r2aR41aHH2Wt9sjeZP7cKFxW/zJ25vgvntYxzT59USLiz2Y0a2HltenSlar7dbf34sMLiw7p107+1WeQ0XcsA/GV1MrvVt6YILy79fbs+tLAjn1LY3wXU8ceah+cwCWJ+Gw015C1qkdYxQetn9EEb57jK65z8dAwuLrB9/n6pHMTtSlnuFMh9Tuv4MgF/c/ZfAwmKr0huCUHGj2HZgvUXhYfP9FF3eHw7ChXV+estRbZmnLYPXH8bjg2EKF9b++T0bR2Eqct5Br452HP5Vhtm9hfL2acXQVNbusTm4sKq/61n6CkbbWXineWneg4VFygv8lxahpDnvaXcpK4cEw4W1Fr1z7sm4+/QDQJ+P0sDC4kj41iCWmIvsXbND5+dQc7CwHrc7JaVJo4nK2u+hr6ravMOFhWujXbdN9xL1vtgsqrKA4cJqGhrbhNatXfjZ+yyvE6r8aLiweOPhubv2xTsgnTDsjWBNhAtL5qrM6UBFs1EHVij4TMCwWCbzd3nkVwbCYA2bNLIPVo3x8KAgS/znSCudAH8LYSFPeo0ONjEthaYxjYunNsJSM8LT+RpTfEsJwTTuy9sIC0kEdDzqND3HyKEYM8aE26VmWQmLkzafNDu5+fxw1IBl4dMQGbuWjKyEhTwjl9ZEJ4zAYSHa1kOjI9HVdriwvjzCfPirtsI8AGBhkehzn0xCyVi07nQSeZHAwqLp2/G6kSHh0GNLGDgNF9bFfF9eNjKFmdk6ZKGdcutgsfz6cjB9T5x/UlvqznQWHfzAhXV39hekgyY2OYoOFcHCErnCBpDIgIcLy2AuE2F0E1hYyDHVk4Uw/gQuLGO5TIQPQ8CwjCVgEic9gwurFCc5nBKhQxIuLOSZydM7E0evAoalHa3QVUdsgGUot5fQfocNS8fn0F7iJQs0LCPpG4OapJagYYkD2vpTXhNADhoW8obvXVwTmgMbFqJDT8RZXaw9cFiDW6bTuthx4LAQGzgP+7o2QA44rIH9rHXPQgtgDZvjP6u9TAUfFmLRcM4w4SGpLbAQQUNtqdP62xs2wELc3w/TiTojyxZYl6kY6kRqy6p+ebcGFuI06h/XruGurC2wClxh1q89/9p038wGWKSIeiSEMecfOvQYglROamQjLBIv8v1htVqds22f0VrNpWwsgNXBNUspNQ4sK2DhQWopLZvv9tsAa5ijB4kaSTbAQnSAMNw3iRpJVsAaYmjJlP2xAtZ3Rrse9SKTjcQOWMjr+3hZqgqsJbCU8hy20LtUUiBLYPXscK3I72czLOT1aWyJLuvYCgv5/dkPcpPQJlj90drKlqG0CBby+zEgAunEnjbBQl4vbrFEuuyHVbAQC7t3XRzlUwnaBQtx/9CxXyxTSCRoGazL4MIfXeJSys5vHawC16GzyahW3NRCWBdcXnh2uwg4DaS2hHbDKrIeYwfFh7Ne75f13vrfAusKjPh6wd+z8O/UCmNEz+2qzMpeWNw/6j0V1VlZCwuHmpfGgupMdb8QFtNJ+HTVSe05aC0szuiHdmvq2eVthMUxybRN+JZ1ouyCVdTx6qDDionlbYTFmRPuO4gMeSg49xthEUadaN5J5pCpoE6mrbAY+a56w4uwLOzg9d5tX8fqQW2nIFRYyTmOQsY9zMJkvTrnbnce1i3RKS8JERaJe/I/L3WGFVBYiPgd1J94VoY1q5aChFWY6HnnDSgUC7ELVrH567RnC1Gx6F8Bqwjl7qxv6dpX3zbbBKvY2aBOAhy2kVSJELthXffMO01LdJmFHUxAG2BdxJwob79xdo/V2eJ/KaxiNjrxtA2v9MBwN/PPHliouJDirDdKe+hgesS0k2Lw1sEqeDEHvedSwILpLvS7HVOWwULFcs88uj5PF0L/6nIxPa+Zjztcp2yFdRVh2HNwdNzN8xc3XRRK3e10sz/ECXWKUgO9cLIT1qd4cXKDKfUKUUqvl+z6GU53shSWGY2wFDTCUtAIS0EjLAWNsBQ0wlLQCEtBcGAphcKakU5lu06lFjdsRsYSiT9J9raRQZlJyVslUek3ODKWR/xZ9RnkIIj14vptpWW7ALMB5ZioWybQCvjQIgNnAa3VEvjz0Ac0sCaTHDQt2lAxfWitAFvxQ6fibVYMlhZrLC4/vA4OTGuLmikO2yCXYHi4GIOygy4r47RPd5aqOKNkb5pJjdxzRBwYoizauaZ5jBolo/9MAokOZMBGSwAAAABJRU5ErkJggg==" alt="">
            <img src="data:image/jpeg;base64,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" alt="">
        </div>
    </footer>
    
</body>

</html>
