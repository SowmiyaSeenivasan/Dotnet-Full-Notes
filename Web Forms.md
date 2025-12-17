## ASP.NET Web Forms

## 1.What is ASP.NET Web Forms? 
A server-side framework to build dynamic, event-driven web pages.

## 2.Main features? 
Event-driven, server controls, ViewState, data binding, rapid development.

## 3.Page Life Cycle? 
Request → Init → Load ViewState → Load → Postback Event → Render → Unload.

## 4.What is PostBack? 
Sending page data to server to process events without changing page URL.

## 5.What is ViewState? 
Stores page/control values between PostBacks in a hidden field.

## 6.Server.Transfer vs Response.Redirect? 
Transfer is server-side without URL change; Redirect is client-side with URL change.

## 7.Cross-Page PostBack? 
Posts page data to a different page using PostBackUrl.

## 8.State Management? 
Preserves data via ViewState, Cookies, QueryString, Session, or Application.

## 9.Session vs Application? 
Session: per user; Application: global for all users.

## 10.Master Pages? 
Define consistent layout with ContentPlaceHolder for multiple pages.

## 11.Server Controls? 
Controls processed on server like TextBox, Button, GridView.

## 12.Data Binding? 
Connect controls to data sources via .DataSource + .DataBind().

## 13.IsPostBack vs !IsPostBack? 
IsPostBack: page submitted; !IsPostBack: first page load.

## 14.Validation Controls? 
Validate input using RequiredField, Compare, Range, Regex, Custom.

## 15.HTTP Handler vs Module? 
Handler: responds to requests (e.g., .ashx); Module: intercepts all requests globally.
