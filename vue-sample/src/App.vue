<template>
  <div id="app" class="app">
    <BasicKLineChart/>
    <ChartTypeKLineChart/>
    <TechnicalIndicatorKLineChart/>
    <CustomThemeKLineChart/>
    <LanguageKLineChart/>
    <TooltipKLineChart/>
    <TimezoneKLineChart/>
    <DrawGraphicMarkKLineChart/>
    <LoadMoreKLineChart/>
    <UpdateKLineChart/>
    <CustomCandleMarkKLineChart/>
    <CustomTechnicalIndicatorMarkKLineChart/>
  </div>
</template>

<script>
import BasicKLineChart from '@/components/BasicKLineChart'
import ChartTypeKLineChart from '@/components/ChartTypeKLineChart'
import TechnicalIndicatorKLineChart from '@/components/TechnicalIndicatorKLineChart'
import CustomThemeKLineChart from '@/components/CustomThemeKLineChart'
import LanguageKLineChart from '@/components/LanguageKLineChart'
import TooltipKLineChart from '@/components/TooltipKLineChart'
import TimezoneKLineChart from '@/components/TimezoneKLineChart'
import DrawGraphicMarkKLineChart from '@/components/DrawGraphicMarkKLineChart'
import LoadMoreKLineChart from '@/components/LoadMoreKLineChart'
import UpdateKLineChart from '@/components/UpdateKLineChart'
import CustomCandleMarkKLineChart from '@/components/CustomCandleMarkKLineChart'
import CustomTechnicalIndicatorMarkKLineChart from '@/components/CustomTechnicalIndicatorMarkKLineChart'

export default {
  name: 'App',
  components: {
    BasicKLineChart,
    ChartTypeKLineChart,
    TechnicalIndicatorKLineChart,
    CustomThemeKLineChart,
    LanguageKLineChart,
    TooltipKLineChart,
    TimezoneKLineChart,
    DrawGraphicMarkKLineChart,
    LoadMoreKLineChart,
    UpdateKLineChart,
    CustomCandleMarkKLineChart,
    CustomTechnicalIndicatorMarkKLineChart
  }
}
</script>

<style>
  body {
    margin: 0;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #191919;
  }

  div, p {
    box-sizing: border-box;
  }

  p {
    margin: 0;
  }

  .app {
    display: flex;
    flex-direction: row;
    justify-content: center;
    flex-wrap: wrap;
    padding: 15px;
  }
  .k-line-chart-container {
    display: flex;
    flex-direction: column;
    margin: 15px;
    border-radius: 2px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, .3);
    background-color: #1f2126;
    width: 620px;
    height: 440px;
    padding: 16px 6px 16px 16px;
  }

  .k-line-chart-title {
    margin: 0;
    color: #E6E8EA;
    padding-bottom: 10px;
  }

  .k-line-chart {
    display: flex;
    flex: 1;
  }
  .k-line-chart-menu-container {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-top: 10px;
    font-size: 12px;
    color: #929AA5;
  }
  .k-line-chart-menu-container button {
    cursor: pointer;
    background-color: #2196F3;
    border-radius: 2px;
    margin-right: 8px;
    height: 24px;
    line-height: 26px;
    padding: 0 6px;
    font-size: 12px;
    color: #fff;
    border: none;
    outline: none;
  }
</style>
