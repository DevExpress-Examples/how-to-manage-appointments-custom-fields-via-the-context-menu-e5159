<!-- default file list -->
*Files to look at*:

* [CustomAppointmentForm.cs](./CS/DXApplication5/CustomAppointmentForm.cs) (VB: [CustomAppointmentForm.vb](./VB/DXApplication5/CustomAppointmentForm.vb))
* [CustomAppointment.cs](./CS/DXApplication5/Data/CustomAppointment.cs) (VB: [CustomAppointment.vb](./VB/DXApplication5/Data/CustomAppointment.vb))
* [CustomResource.cs](./CS/DXApplication5/Data/CustomResource.cs) (VB: [CustomResource.vb](./VB/DXApplication5/Data/CustomResource.vb))
* [DataHelper.cs](./CS/DXApplication5/Data/DataHelper.cs) (VB: [DataHelper.vb](./VB/DXApplication5/Data/DataHelper.vb))
* [Form1.cs](./CS/DXApplication5/Form1.cs) (VB: [Form1.vb](./VB/DXApplication5/Form1.vb))
<!-- default file list end -->
# How to manage appointment's custom fields via the context menu


<p>This example demonstrates how to add an additional menu item that represents a custom field to the default appointment's context menu. To achieve the goal, handle the PopupMenuShowing event of the SchedulerControl.  In this sample, an end-user can change the custom field value ("Priority") via the dropdown list in the appointment's context menu or edit it in a custom Edit Appointment Form.</p>

<br/>


