<template>
  <div id="app">
    <div class="wpbox">
    <div class="bnt">
      <h1 class="tith1 fl">交通分析</h1>
      <div class=" fr topbnt_right">
      </div>
    </div>
    <!-- bnt end -->
    <div class="left1">
      <div class="aleftboxttop pt1">
        <h2 class="tith2">进州车辆情况</h2>
        <div class="lefttoday_tit" style=" height:8%">
          <p class="fl">地区：甘孜</p>
          <p class="fm">周期：每日</p>
          <p class="fr">2018-06-14</p>
        </div>
        <div class="tlbox">
        </div>

        <!-- lefttoday_number end -->
      </div>
      <div class="aleftboxtmidd">
        <h2 class="tith2 pt2">出州车辆情况</h2>
        <div class="lefttoday_tit" style=" height:8%">
          <p class="fl">地区：甘孜</p>
          <p class="fm">周期：每日</p>
          <p class="fr">2018-06-14</p>
        </div>
        <div class="tlbox">
        </div>
      </div>
      <div class="aleftboxtbott">
        <h2 class="tith2">总体驾驶人统计</h2>
        <!-- <div id="aleftboxtmidd" class="aleftboxtbott_cont2" ></div> -->
      </div>
    </div>
    <!--  left1 end -->
    <div class="mrbox">
      <div class="mrbox_topmidd" style="width: 69%;">
        <div class="amiddboxttop">
          <h2 class="tith2 pt1">实时地图</h2>
          <div class="hot_map" id="topmap">

          </div>
        </div>
        <!--  amiddboxttop end-->
        <div class="amidd_bott">
          <div class="amiddboxtbott1 fl">
            <h2 class="tith2 pt1">每日上户车辆</h2>
          </div>

          <div class="amiddboxtbott2 fl">
            <h2 class="tith2 pt1">高危车辆统计</h2>
            <!-- <div id="arightboxbott" class="amiddboxtbott2content"></div> -->
          </div>
        </div>
        <!-- amidd_bott end -->
      </div>
      <!-- mrbox_top end -->
      <div class="mrbox_top_right">
        <div class="arightboxtop">
          <h2 class="tith2">今日办驾照统计（雷达图）</h2>
          <!-- <div id="aleftboxtbott"  class="aleftboxtbott_contr"></div> -->
        </div>
        <div class="arightboxbott">
          <h2 class="tith2 ">今日新增驾驶人统计</h2>

          <!-- <div id="aleftboxtmiddr" class="arightboxbottcont2"></div> -->
        </div>
      </div>
      <!-- mrbox_top_right end -->
    </div>
  </div>

  </div>
</template>

<script>

export default {
  name: 'App',

}
</script>

<style lang="less">
#app {
  height: calc(100% - 10px);
}
</style>
