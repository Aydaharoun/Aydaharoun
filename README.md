Rana:
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp2());
}

class MyApp2 extends StatelessWidget {
  const MyApp2({Key? key}) : super(key: key);

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      home: const MyHomePage(title: ' Home Page'),
    );
  }
}

class MyHomePage extends StatefulWidget {
  const MyHomePage({Key? key, required this.title}) : super(key: key);

  final String title;

  @override
  State<MyHomePage> createState() => _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {
  void _incrementCounter() {
    setState(() {});
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.white10,
      appBar: AppBar(
          title: Row(
        children: const [
          CircleAvatar(
            radius: 15.0,
          ),
          SizedBox(
            width: 10.0,
          ),
          Text('Profile'),
        ],
      )),

      body: Padding(
        padding: const EdgeInsets.all(50.0),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: <Widget>[
            Expanded(
              child: Row(
                children: [
                  Row(
                    children: [
                      ElevatedButton(
                        onPressed: () {},
                        onLongPress: () {},
                        child: const Text('KHARTOUM'),
                      ),
                      const SizedBox(
                        width: 20.0,
                      ),
                      ElevatedButton(
                        onPressed: () {},
                        onLongPress: () {},
                        child: const Text('BAHRI'),
                      ),
                      const SizedBox(
                        width: 20.0,
                      ),
                      ElevatedButton(
                        onPressed: () {},
                        onLongPress: () {},
                        child: const Text('OM_DORMAN'),
                      ),
                    ],
                  ),
                ],
              ),
            ),
            const SizedBox(
              height: 01.0,
            ),

            Expanded(
              child: Column(
                children: [
                  Column(
                    children: [
                      const CircleAvatar(
                        radius: 15.0,
                      ),
                      TextButton(
                        onPressed: () {},
                        child: const Text('llk'),
                      ),
                      const SizedBox(
                        height: 15.0,
                      ),
                      const CircleAvatar(
                        radius: 15.0,
                      ),
                      TextButton(
                        onPressed: () {},
                        child: const Text('llk'),
                      ),
                      const SizedBox(
                        height: 15.0,
                      ),
                      const CircleAvatar(
                        radius: 15.0,
                      ),
                      TextButton(
                        onPressed: () {},
                        child: const Text('llk'),
                      ),
                    ],
                  ),
                ],
              ),
            ),

            // TextField(),
            //   Icon(Icons.search),
            //   SizedBox(height: 30.0,),
            //   CircleAvatar(
            //     radius: 15.0,
            //   ),

//   SizedBox(
            //     width: 10.0,
            //   ),
            //   Text(
            //     'Insert Your Appoiment ',
            //   ),
            //   SizedBox(
            //     width: 10.0,
            //   ),
            //   CircleAvatar(
            //     radius: 15.0,
            //   ),
            //   SizedBox(
            //     width: 10.0,
            //   ),
            //   Text(
            //     'Insert Your Appoiment ',
            //   ),
            //   SizedBox(
            //     width: 10.0,
            //   ),
            //   CircleAvatar(
            //     radius: 15.0,
            //   ),
            //   SizedBox(
            //     width: 10.0,
            //   ),
            //   Text(
            //     'Insert Your Appoiment ',
            //   ),
            //   SizedBox(
            //     width: 10.0,
            //   ),
            //   CircleAvatar(
            //     radius: 15.0,
            //   ),
            //   SizedBox(
            //     width: 10.0,
            //   ),
            //   Text(
            //     'Insert Your Appoiment ',
            //   ),
          ],
        ),
      ),
      // floatingActionButton: FloatingActionButton(
      //     onPressed: _incrementCounter,
      //     tooltip: 'insert',
      //     child: const Icon(Icons.add)),
      // This trailing comma makes auto-formatting nicer for build methods.
    );
  }
}
