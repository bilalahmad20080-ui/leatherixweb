LEATHERIX WEBSITE - HOW TO USE

1. Upload everything in this folder (index.html + the images folder) to your hosting, keeping the same structure.
2. To add a photo to a product:
   - Put the photo in images/jackets/ or images/gloves/ (or create a new folder, e.g. images/suits/)
   - Open index.html and add its path to that product's list, e.g.  "images/gloves/glove_13.png"
   - Optional: add a small copy in images/thumbs/<same folder>/<same name>.webp for fast thumbnails
     (if it is missing, the full photo is used automatically).
3. Contact details are near the top of the script in index.html (SITE: whatsapp, email, ig).
   The email is still a placeholder: info@leatherix.com

ARTICLE NUMBERS
- Leather Jackets photos are LJ-001, LJ-002 ... and Riding Gloves photos are RG-001, RG-002 ... (numbered in list order).
- The number shows on the photo, under each thumbnail, in the product window, and inside the WhatsApp / quote message.
- To use your own numbers, add  art:["A-101","A-102",...]  to that product in index.html.
- To number another product, add  pre:"XX"  to it (for example pre:"RS" for Riding Suits).

VESTS
- Men's Leather Vests photos: images/vests-men/  (article numbers MV-001 ... MV-007)
- Women's Leather Vests photos: images/vests-women/  (article numbers WV-001 ... WV-008)
