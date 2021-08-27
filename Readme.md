<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128567905/12.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4141)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/TooltipAppearanceCustomization/MainPage.xaml) (VB: [MainPage.xaml](./VB/TooltipAppearanceCustomization/MainPage.xaml))
<!-- default file list end -->
# How to customize the appearance of a series tooltip
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4141)**
<!-- run online end -->


<p>This example demonstrates how to change the appearance  of a series tooltip via its template.</p><p>To do this, you need to create a <strong>System.Windows.DataTemplate</strong> object that specifies the appearance of series tooltips and assign it to the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsSeries_ToolTipSeriesTemplatetopic"><u>Series.ToolTipSeriesTemplate</u></a> property. In this example, this has been done for the first series.</p><p><br />
Note that before the tooltip customization, you need to set the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsChartControl_ToolTipEnabledtopic"><u>ChartControl.ToolTipEnabled</u></a> and <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsToolTipOptions_ShowForSeriestopic"><u>ToolTipOptions.ShowForSeries</u></a> properties to<strong> true</strong> to show the tooltip for a series. </p><p>It is also necessary to specify a display name for each series displayed on the tooltip via the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsSeries_DisplayNametopic"><u>Series.DisplayName</u></a>  property. </p><br />
<br />
<br />


<br/>


