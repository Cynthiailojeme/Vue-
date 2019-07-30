<template>
    <div class="lower">
        <div class="smaller">
            <p class="percent">94.6%</p>
            <p class="text2">Student Attendance</p>
                <br>
            <p class="percent2">6</p>
            <p class="text2">No of students absent</p>
            
            <img src="../assets/plus4.png" class="graphimages"/>
            <img src="../assets/minus12.png" class="graphimages2"/>

        </div>

        <div class="larger">
            <ul>
                <li>NAME</li>
                <li>CLASS</li>
                <li>NUMBER OF DAYS ABSENT</li>
            </ul>
            <hr>
        </div>

    </div>
</template>

<style>
.lower{
    margin-left: 280px;
    display: flex;
    align-items: flex-start;
    }
    .smaller {
        width: 269px;
        height: 233px;
        background: #FFFFFF;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 7.51481px 37.574px rgba(0, 0, 0, 0.07);
        border-radius: 7.51481px;
        margin-right: 30px;
    }
    .larger {
        width: 823px;
        height: 233px;
        background: #FFFFFF;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 7.51481px 37.574px rgba(0, 0, 0, 0.07);
        border-radius: 7.51481px;
    }
    .percent {
        font-weight: bold;
        font-size: 36px;
        color: #3B3B3B;
        margin-left: 20px;
        margin-bottom: -10px;
        margin-top: 20px;
    }
    .percent2 {
        font-weight: bold;
        font-size: 36px;
        color: #3B3B3B;
        margin-left: 50px;
        margin-bottom: -10px;
        margin-top: 20px;
    }
    .text2 {
        font-size: 10px;
        color: #BDBDBD;
        margin-left: 20px;
    }
    .graphimages {
        float: right;
        margin-top: -190px;
        margin-right: 10px;
    }
    .graphimages2 {
        float: right;
        margin-top: -70px;
        margin-right: 10px;
    }
    .larger hr{
        width: 740px;   
        border: 0.626846px solid #E0E0E0;
        margin-left: 20px;
        margin-right: 20px;
    }
    .larger ul {
        list-style: none;
        font-weight: 600;
        font-size: 10px;
        line-height: 16px;
        display: flex;
        color: #3B3B3B;
    }
    .larger li {
        margin-right: 150px;
        margin-top: 15px;
        margin-bottom: -15px;
    }
</style>

