# nuke-toolset-Split_EXR
A simple and fast way to split EXR files in Nuke — just like PSD layers. Choose which passes go into your main branch, send technical ones aside, preview layers instantly, and keep your node tree clean.

I’d love to share a little tool I’ve been working on for handling EXRs.

As you know, splitting EXRs is something we all have to do from time to time — and it can eat up a lot of time. So I built a small tool, kind of like PSD layers, but for EXR. The idea is simple: you can decide which passes go into your main branch, and which ones stay on the side as utility passes.

Here’s how it works:

Set your viewer to the EXR and select it

Go to Tools → Split EXR

If you want, hit Open Preview to quickly check the layers (works if your viewer is on the EXR)

Drag the layers between Main (color) and Utility

Hit OK — and you’re done ✅

This is just the first version, but I’m planning to add a few cool things later:👉 an option to choose vertical or horizontal layouts for the node tree👉 automatic light groups👉 easier ways to organize passes

Installation: just copy the split_EXR file into your .nuke folder and add the lines from menu.py.
