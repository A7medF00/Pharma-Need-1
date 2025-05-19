# Pharma-Need-1
// main.dart impor
'package:flutter/material.dart'; import 'screens/splash_screen.dart';

void main() { runApp(PharmaNeedApp()); }

class PharmaNeedApp extends StatelessWidget { @override Widget build(BuildContext context) { return MaterialApp( title: 'PharmaNeed', debugShowCheckedModeBanner: false, theme: ThemeData( primarySwatch: Colors.blue, fontFamily: 'Cairo', ), home: SplashScreen(), ); } }
