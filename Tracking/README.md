(2018.11.05)
IOU tracker: https://github.com/HoracceFeng/iou-tracker
事实上不是一个tracker的算法，使用detection框也根本不能说是没有使用image information。但是此文对traffic_ID的确定提供了思路。
- sign_filter会用这里面的IOU+trend思想作更新
- 可能可以为 traffic_cognition_system 重新定义个 用trend和iou修正的tracker.
