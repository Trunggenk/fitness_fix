Mã nguồn tham khảo từ : https://github.com/igrisan/fitness_workout_app_flutter_3_ui

Mã nguồn ML : https://www.youtube.com/watch?v=bHyihP2XjqA&list=PL-Y17yukoyy0sT2hoSQxn1TdV0J7-MX4K&index=8
### Huướng dẫn cài đặt
- Cài đặt Flutter: https://flutter.dev/docs/get-started/install
- Cài đặt Android Studio: https://developer.android.com/studio
- Cài đặt Visual Studio Code: https://code.visualstudio.com/
- Bật Android SDK CommandLine Toolls trong SDK Manager -> SDK Tools
- Cài đặt Python, và mini conda.


### Kiến trúc thư mục
*Thư mục server* /server
...
Hiện chưa cần quan tâm
### Hướng dẫn chạy
- flutter run
- chọn Emulator API 35 trở lên.


Đã fix hết lối đến từ Flutter:
- Lỗi phiên bản Java run time cần nâng gradle lên ^8.0.0
- Lỗi namespace cần sửa replace toàn bộ namespace thành com.example.fitness 
- lỗi flchat: cách sửa lỗi:

"Created a custom widget named FLChartBarWidget (same as the class name in my code).

Copied the code example of the bar chart taken from here:
https://github.com/imaNNeo/fl_chart/blob/main/example/lib/presentation/samples/bar/bar_chart_sample1.dart


The original code example contains 2 url links which failed to be compiled in FF:

import 'package:fl_chart_app/presentation/resources/app_resources.dart';
import 'package:fl_chart_app/util/extensions/color_extensions.dart';

So I've copied their content inside the bottom of my custom widget code (see below).

The code compiled successfully inside the custom code section

Integrated my FLChartBarWidget component inside one of my project pages and everything seemed to work properly (the Mingguan widget at the bottom):"

# Vô vàn lỗi khác :> dmm Flutter mỗi phiên bản của plugins lại thay đổi cấu trúc.


