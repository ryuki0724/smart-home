<template>
  <div id="weather-card">
    <div class="left-panel panel">
      <div class="date">星期一, 2024年4月24日</div>
      <div class="city">前鎮區</div>
      <div class="temp">
        <img src="../components/icons/ts.png" alt="" width="60" />
        27&deg;
      </div>
    </div>
    <div class="right-panel panel">
      <img src="../components/icons/mumbai.png" alt="" width="160" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'WeatherCard'
}
</script>

<style>
#weather-card
{
  position: absolute;
  width: 355px;
  height: 125px;
  margin-top: 150px;
  right: 15px;
  background-color: #fcfdfd;
  border-radius: 9px;
  padding: 25px;
  padding-right: 30px;
  box-shadow: 0px 31px 35px -26px #080c21;
}

.date
{
  font-size: 14px;
  font-weight: bold;
  color: rgba(0,0,0,0.5);
}

.city
{
  font-size: 21px;
  font-weight: bold;
  text-transform: uppercase;
  padding-top: 5px;
  color: rgba(0,0,0,0.7);
}

.temp
{
  font-size: 81px;
  color: rgba(0,0,0,0.9);
  font-weight: 100;
}

.panel
{
  display: inline-block;
}

.right-panel
{
  position: absolute;
  float: right;
  top: 0;
  margin-top: 35px;
  padding-left: 10px;
}
</style>
