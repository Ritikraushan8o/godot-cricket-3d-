# Godot 4 Cricket 3D (Joystick Controlled)

**यह एक Godot 4 में बना हुआ 3D क्रिकेट गेम है जिसमें मोबाइल जॉयस्टिक से बैट कंट्रोल किया जाता है।**  
This is a 3D Cricket Game made in Godot 4 with mobile joystick controls for the bat.

## फीचर्स / Features:
- 3D पिच, बैट और बॉल
- मोबाइल जॉयस्टिक से बैट घुमाएं
- फिजिक्स-आधारित बॉल मूवमेंट
- Android export-ready project

## उपयोग कैसे करें / How to Use:
1. Godot 4 में प्रोजेक्ट खोलें (`project.godot`)
2. `Main.tscn` सीन को रन करें
3. मोबाइल पर चलाने के लिए Android export सेट करें

## Controls:
- Joystick (left) = बैट रोटेशन
- Touch anywhere to hit the ball

## योगदान / Contribute:
आप बॉलिंग, स्कोरिंग, और एनिमेशन जोड़ सकते हैं! Pull request का स्वागत है।

---

**Made with [Godot Engine](https://godotengine.org)**

godot-cricket-3d/
├── project.godot
├── README.md
├── Main.tscn
├── assets/
│   ├── bat.glb
│   ├── ball.glb
│   └── pitch.glb
├── scripts/
│   ├── Bat.gd
│   ├── Ball.gd
│   └── Joystick.gd
└── ui/
    └── joystick.tscn
