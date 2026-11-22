# Anuskha Saha: paintings and photographs

Live site: https://kenposable.github.io/gallery/

A 3D gallery wall and a shop/grid view for original paintings and photographs.

## How it works
- `index.html`: the whole website (3D gallery, shop, photo grid, bag, owner tools).
- `data/gallery.json`: the database. Every painting and photograph, plus site settings.
- `media/`: the images. Each upload is stored as a full-size image and a thumbnail.

## Adding work
Open https://kenposable.github.io/gallery/#owner and sign in with a fine-grained GitHub token
that has **Contents: Read and write** on this repository only. Your tools then appear in the
top bar: add paintings, add photos, edit, delete and change site settings. Each save is a commit
to this repository, and GitHub Pages updates the live site about a minute later.

Orders arrive on WhatsApp or by email, using the number and address set in Site settings.
