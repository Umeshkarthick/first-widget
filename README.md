import 'package:flutter/material.dart';

void main() {
  runApp(const MainApp());
}

class MainApp extends StatelessWidget {
  const MainApp({super.key});

  @override
  Widget build(BuildContext context) {
    return  MaterialApp(
      home: Scaffold(
        body: Center(
          child: Container(
            height: 200,width:200,
            alignment: Alignment.center
            ,decoration: BoxDecoration
            (borderRadius: BorderRadius.circular(100),
            color: Colors.blue),
            
            child:Column(
              mainAxisAlignment: MainAxisAlignment.center,
              crossAxisAlignment: CrossAxisAlignment.center,
              children: [
                Container(
              decoration: BoxDecoration(
                color: Colors.red,
                borderRadius: BorderRadius.circular(100)),
                padding:EdgeInsets.all(10),
          child: Text('Hello World!'),),
          
          Container(
              decoration: BoxDecoration(
                color: Colors.red,
                borderRadius: BorderRadius.circular(100)),
                padding:EdgeInsets.all(10),
          child: Text('Hello World!'),),
              ],
             
            )
        ),
      ),
    ));
  }
}
