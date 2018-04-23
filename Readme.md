# How to customize the appearance of a series tooltip


<p>This example demonstrates how to change the appearance  of a series tooltip via its template.</p><p>To do this, you need to create a <strong>System.Windows.DataTemplate</strong> object that specifies the appearance of series tooltips and assign it to the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsSeries_ToolTipSeriesTemplatetopic"><u>Series.ToolTipSeriesTemplate</u></a> property. In this example, this has been done for the first series.</p><p><br />
Note that before the tooltip customization, you need to set the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsChartControl_ToolTipEnabledtopic"><u>ChartControl.ToolTipEnabled</u></a> and <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsToolTipOptions_ShowForSeriestopic"><u>ToolTipOptions.ShowForSeries</u></a> properties to<strong> true</strong> to show the tooltip for a series. </p><p>It is also necessary to specify a display name for each series displayed on the tooltip via the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsSeries_DisplayNametopic"><u>Series.DisplayName</u></a>  property. </p><br />
<br />
<br />


<br/>


