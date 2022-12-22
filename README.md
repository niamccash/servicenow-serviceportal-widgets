# ServiceNow Service Portal Widgets
Custom ServiceNow Service Portal widgets

## [SC Category Page v1](/cccd464b2fb311545dcb59ab2799b6b1/update/sp_widget_ad8178f52fce59105dcb59ab2799b6c6.xml)
Lists all subcategories under the selected category (as specified in the `sys_id` parameter in the URL). In the image example below, parent category is '*Hardware*'. 

URL format: `https://[INSTANCE].service-now.com/[PORTAL]/?id=[PAGE_ID]&sys_id=[PARENT_CATEGORY_ID]`

![Subcategories as cards](https://user-images.githubusercontent.com/39105458/208762016-97e0fb4f-3813-4129-90ba-e1673e3161c8.png)

If a Category is not specified in the URL, then the widget will attempt to get all the categories from the Catalogs associated with the Portal (as defined in Portal Catalog `[m2m_sp_portal_catalog]` records). 

If the Portal has no specific Catalogs associated to it, then it will show all parent categories from all catalogs.

**Available options**

![SC Category Page v1 widget configuratble options](https://user-images.githubusercontent.com/39105458/208799911-74eee707-644c-4921-be42-72320a9e7d8f.png)




## Other Resources

* [Service Portal: Widget Library](https://github.com/platform-experience/serviceportal-widget-library) - A collection of Service Portal custom widgets and a component of the Innovation Library.
