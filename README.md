# Tablayout
修改系统tablayout:设置指示器宽高颜色 区分选中状态来设置文字大小 加粗.

//设置tab 未选中/选中 文字颜色
 tabLayout.setTabTextColors(getResources().getColor(R.color.text_color_black), getResources().getColor(R.color.text_color_black));
 //设置tab未选中/选中 文字大小
tabLayout.setTabTextSize(40, 43);
//设置tab文字选中时加粗
tabLayout.setTextSelectedBold(true);
//设置指示器宽度
 tabLayout.setTabIndicatorWidth(40);
 //设置指示器高度
tabLayout.setSelectedIndicatorHeight(6);
