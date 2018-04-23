# How to build non-linear layout via LayoutControl 


<p>This example shows how to arrange items within a <a href="https://documentation.devexpress.com/#WPF/CustomDocument8147">LayoutControl</a>, forming a non-linear layout. To create a layout, <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfLayoutControlLayoutItemtopic">items</a> are combined into <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfLayoutControlLayoutGrouptopic">groups</a> and the groups are combined into other groups.</p>
<p>Various group visual styles are demonstrated. <strong>Group 1</strong> is rendered using the <strong>GroupBox</strong> visual style (the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutGroup_Viewtopic">View</a> property is set to <strong>GroupBox</strong>), which allows a header to be displayed. There is also a group that represents items as tabs (its <strong>View</strong> property is set to <strong>Tabs</strong>). Other groups are painted without a header and borders.</p>
<p>For <strong>Group 1</strong>, the collapsing feature is enabled via the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutGroup_IsCollapsibletopic">LayoutGroup.IsCollapsible</a> property, allowing an end-user to collapse the group's contents.</p>
<p>For the tabbed group and the group that displays <strong>Item 2</strong> and <strong>Item 3</strong>, horizontal sizing is enabled via the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutControl_AllowHorizontalSizingtopic">LayoutControl.AllowHorizontalSizing</a> attached property. Vertical sizing is enabled for <strong>Item 4</strong> via the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutControl_AllowVerticalSizingtopic">LayoutControl.AllowVerticalSizing</a> attached property.</p>
<p>For items 1, 2, 3, 4 and 6, the <strong>VerticalAlignment</strong> property is set to <strong>Stretch</strong>. These items are stretched when the LayoutControl's height is changed. For <strong>Item 9</strong> and <strong>Item 11</strong>, the <strong>HorizontalAlignment</strong> property is set to <strong>Left</strong> and <strong>Right</strong>, respectively. These items have a fixed width and are not stretched when the LayoutControl's width is changed.</p>

<br/>


