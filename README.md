# ServiceNow Resources

## Table of Contents
1. [Development Resources](#development-resources)
1. [Websites](#websites)
1. [Misc](#misc)


## Development Resources
- [ServiceNow Standards Framework](https://github.com/iamkalai/SNStandardsFramework) by [@iamkalai](https://github.com/iamkalai)
- [Interface Design Patterns for Script Includes](https://codecreative.io/servicenow/interface-design-patterns-for-script-includes) by [@tltoulson](https://github.com/tltoulson)
- [Glider.js](https://github.com/tltoulson/Glider.js) by [@tltoulson](https://github.com/tltoulson)
- [Script Execution Order](https://docs.servicenow.com/bundle/jakarta-servicenow-platform/page/script/general-scripting/reference/r_ExecutionOrderScriptsAndEngines.html)
- [Script evaluation of fields by data type](https://docs.servicenow.com/bundle/jakarta-servicenow-platform/page/script/general-scripting/reference/r_ScriptingOfFieldTypes.html)

### Service Portal
- [Unofficial Service Portal Docs](https://github.com/newrocketinc/service-portal-docs)
- [Service Portal Best Practices](https://github.com/platform-experience/serviceportal-best-practice)
- [Widget Anatomy](https://www.youtube.com/watch?v=MllpUpcl6TI)


### Web Services
- [Sample REST HTTP Request](https://gist.github.com/bryanbarnard/1f2d9e819dfb5fad41a3)


## Websites
- [serviceportal.io](https://serviceportal.io)





## Misc
- If a company is using SSO and you are being redirected, try `<instance-name>.service-now.com/login.do` or `<instance-name>.service-now.com/side_door.do`


### Service Portal Structure
- Portal Record
    - Theme [Reference]
    - URL Suffix


- Theme Record
    - Header Widget Record [Reference]
    - Footer Widget Record [Reference]
    - CSS Variables
    - CSS Includes [Reference]
    - JavaScript Includes [Reference]

- Page Records


- Widget Records


- Widget Instance Records



#### Tables
- Service Portal [`sp_portal`]
- Theme [`sp_theme`]
- Page [`sp_page`]
- Widget [`sp_widget`]
- Instance [`sp_instance`]
    - Instance of Carousel [`sp_instance_carousel`]
    - Instance with Link [`sp_instance_link`]
    - Instance with Menu [`sp_instance_menu`]
    - Instance with Table [`sp_instance_table`]
        - Instance of Simple List [`sp_instance_vlist`]
- Carousel Slide [`sp_carousel_slide`]
- Menu Item [`sp_rectangle_menu_item`]
- Header | Footer [`sp_header_footer`]
- Search Source [`m2m_sp_portal_search_source`]
- Search Group [`sp_search_group`]
- Widget Dependency [`sp_dependency`]
- Widget Dependency [`m2m_sp_widget_dependency`]
- Angular Providers [`m2m_sp_ng_pro_sp_widget`]
- Service Portal Log Entry [`sp_log`]
- Service Portal UI Formatter [`sp_ui_formatter`]
- Angular ng-template [`sn_ng_template`]
- Widget Script Include [`m2m_sp_widget_script_include`]
- Service Portal Documentation [`sp_documentation`]
- JS Includes [`m2m_sp_theme_js_include`]
- JS Include [`sp_js_include`]
- Stylesheets [`m2m_sp_theme_css_include`]
- CSS Include [`sp_css_include`]
