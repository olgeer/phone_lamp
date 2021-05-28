# phone_lamp

Flutter 闪光灯操作

此插件是 在 lamp 的基础上修改的，因为 lamp 的android端无法正常工作
附上lamp地址：https://pub.dev/packages/lamp

并升级到了Null safety版本

// Import package
import 'package:phone_lamp/phone_lamp.dart';

// Turn the lamp on:
PhoneLamp.turnOn();

// Turn the lamp off:
PhoneLamp.turnOff();

// Turn the lamp with a specific intensity (only affects iOS as of now):
PhoneLamp.turnOn(intensity: 0.4);

// Check if the device has a lamp:
bool hasLamp = await PhoneLamp.hasLamp;