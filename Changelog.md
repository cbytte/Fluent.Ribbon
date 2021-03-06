# Changelog for Fluent.Ribbon

## 3.1.0 (not release yet)
- Fixed: #11 (ContextMenu and Popup has 10px space at bottom and right side)
- Fixed: #18 (Tabs are disabled when using datatemplate for viewmodel in window content)
- Fixed: #13 (Backstage does not open at application start anymore)
- Fixed: #17 (Problem with Mouse Capture on SplitButton)
- Added DropDownButton.ClosePopupOnMouseDown property which defaults to false. If true, it will close the drop down popup automatically when a mouse down event occurs.
- Fixed: 22521 (RibbonWindow is activated when focus is lost after Alt+Tab)
- Fixed: 22523 (Typo in Generic.xaml)
- Renaming InnerBackstageTabCotrolItem to InnerBackstageTabControlItem

## 3.0.3
- Fixed: 22519 (Normalize button closes application) Thanks to GeertvanHorrik for finding out that the version of Microsoft.Windows.Shell for .NET 4.0 that was used is buggy.

## 3.0.2
- Fixed: 22519 (Normalize button closes application)

## 3.0.1
- Fixed an issue with closed direct member menus (keytips were always redirected for direct childs)
- Fixed: 22518 (Faulty white margin on the right and left of the window body)
- Fixed: 22516 (Issues with backstage content localization using WPF Localization Extension)

## 3.0.0
- Too much work to write down changes made in 4 years. Please have a look at [changes in version 3.0](https://fluent.codeplex.com/wikipage?title=Changes%20in%20version%203.0&referringTitle=Documentation).