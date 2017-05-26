Snacky Snackbar控件的升级版

Snackbar.LENGTH_SHORT// 短时间显示，然后自动取消
Snackbar.LENGTH_LONG// 长时间显示，然后自动取消
Snackbar.LENGTH_INDEFINITE// 不消失显示，除非手动取消

android.support.design.widget.CoordinatorLayout控件包裹后
如果调用setActivty(MainActivity.this)方法，FloatingActionButton不随Snacky控件出现后上移
如果调用setView(v)方法，FloatingActionButton会随着Snacky控件出现后上移