# Realm Memory Leak

Launch the app with Leaks, and a memory leak occurs as a result on instantiating the Realm.

Commenting out ```let realm = try! Realm()``` fixes the leak.
