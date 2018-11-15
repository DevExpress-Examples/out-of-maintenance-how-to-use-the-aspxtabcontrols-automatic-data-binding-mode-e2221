<!-- default file list -->
*Files to look at*:

* [TabControlDataSource.xml](./CS/WebSite/App_Data/TabControlDataSource.xml) (VB: [TabControlDataSource.xml](./VB/WebSite/App_Data/TabControlDataSource.xml))
* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to use the ASPxTabControl's automatic data binding mode


<p>This sample demonstrates how to bind the ASPxTabControl to data without manually setting the control's data-related properties.<br />
The ASPxTabControl's data source is set to an XmlDataSource component that is used to retrieve data from an XML file. The XmlDataSource's XPath property is defined explicitly.<br />
Based on the source data, the ASPxTabControl populates its Tabs collection with automatically created Tab objects. Tab object characteristics (such as text, image, navigate location, tooltip text, etc.) are obtained from the XML file's node attributes.</p><p>This example demonstrates the ASPxTabControl's ability to automatically retrieve tab characteristics from node attributes whose names coincide with property names of a Tab object. For this purpose, node attributes are named as<strong> ActiveTabImageUrl</strong>,<strong> Name</strong>,<strong> NavigateUrl</strong>, <strong>TabImageUrl</strong>, <strong>Text</strong> and <strong>ToolTip</strong> in this demo. Note that the name match is not case sensitive.</p>

<br/>


