# 🪟 Unity Custom Editor Window for ScriptableObject Serialization & Addressables Integration

This repository presents a **custom-built Editor Window** designed to automate and simplify the management of complex **ScriptableObject** data structures in Unity. This tool supports full **JSON serialization and deserialization**, and integrates seamlessly with Unity's **Addressables system** — all from a user-friendly, tabbed editor interface.

[![Watch the Demo](https://img.youtube.com/vi/worTyFjI8Jg/0.jpg)](https://youtu.be/worTyFjI8Jg)

---

## ✨ Key Features

- 🧭 **Multi-tabbed Custom Editor Window** for a clean and modular interface.
- 📝 **Export ScriptableObjects to JSON**, with full support for:
  - ✅ Nested classes
  - ✅ Enums
  - ✅ Polymorphic data structures and inheritance
- 📦 **Regenerate ScriptableObjects from JSON**, preserving:
  - Data integrity
  - Field types
  - Nested structures
- 🧠 **Accurate type mapping** based on base and derived classes.

---

## 📦 Addressables Integration

This tool goes a step further by automating asset setup for Unity’s **Addressable Asset System**:

- 📁 All generated assets are added to the **correct Addressable Groups**.
- 🏷️ Assets are tagged with **appropriate Addressable labels** based on their type/configuration.
- 📤 Ready for remote content updates, builds, and clean runtime use — no manual setup required.

---

## 🧠 Why It Matters

Managing complex data-driven systems in Unity often leads to repetitive tasks, error-prone manual setups, and bloated inspectors. This Editor Window:

- Automates asset generation from config files
- Supports **version control-friendly JSON** structures
- Enforces clean data pipelines for modular systems

Ideal for games with **procedural content, large item databases, or layered gameplay mechanics** powered by ScriptableObjects.

---

## 📹 Demo Video

🔗 See the full tool in action:  
👉 [https://youtu.be/worTyFjI8Jg](https://youtu.be/worTyFjI8Jg)

---

## ⚠️ NDA Notice

Due to a **non-disclosure agreement (NDA)** with my current company, I’m unable to share the actual source code of this tool. However, the video demo provides a detailed breakdown of its features and capabilities.

---

## 🔧 Built With

- Unity Editor API (CustomWindow, EditorGUILayout, Tabs)
- Newtonsoft JSON (or Unity's JsonUtility)
- ScriptableObject architecture with inheritance and polymorphism
- Addressables API (`AddressableAssetSettings`, `AssetLabelReference`, etc.)

---

## 📂 Project Status

This tool was developed and deployed as part of a real-world game development pipeline, dramatically improving productivity for large content teams.

---