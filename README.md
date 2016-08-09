# -高仿QQ消息未读-

   引入WHC_BadgeView.h 头文件

     WHC_BadgeView  * badgeView = nil;//初始化控件
    badgeView = [[WHC_BadgeView alloc]initWithSuperView:cell position:CGPointMake(cell.frame.size.width - 50.0, 15.0) radius:10.0];
    [badgeView setBadgeNumber:indexPath.row];//设置显示的消息数量

