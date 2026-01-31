===========================================
Haseeb Footwear Footwear STORE - SETUP INSTRUCTIONS
===========================================

✅ WEBSITE PAGES:
1. index.html    - Home Page (Featured products)
2. shop.html     - Shop Page (All products with Load More)
3. contact.html  - Contact Page
4. style.css     - All styles
5. script.js     - JavaScript for shop page

✅ FEATURES:
- Responsive hamburger menu
- Social media icons (Facebook, Instagram, TikTok, YouTube)
- WhatsApp integration on all buy buttons
- Product filtering by categories
- Load More functionality for shop page
- Professional luxury design
- Mobile-friendly on all devices

✅ SETUP STEPS:

1. WHATSAPP NUMBER SETUP:
   - Open all HTML files (index.html, shop.html, contact.html)
   - Search for "923275569530" (Replace with your number)
   - Format: 923275569530 (without + or spaces)
   - Total places: 9 times in index.html, 18+ times in shop.html, 1 time in contact.html

2. SOCIAL MEDIA LINKS:
   - Open all HTML files
   - Search for "https://facebook.com" and replace with your links
   - Do same for Instagram, TikTok, and YouTube

3. IMAGES SETUP:
   - Create "images" folder in your project
   - Download these images (Right click → Save Image As):

   Hero Background:
   https://images.unsplash.com/photo-1547996160-81cdc5d82b04?w=1920&q=80

   Product Images (6 needed):
   https://images.unsplash.com/photo-1523170335258-f5ed11844a49?w=800&q=80
   https://images.unsplash.com/photo-1553062407-98eeb64c6a62?w=800&q=80
   https://images.unsplash.com/photo-1551816230-ef5deaed4a26?w=800&q=80
   https://images.unsplash.com/photo-1587836374828-4dbafa94cf0e?w=800&q=80
   https://images.unsplash.com/photo-1611591437281-8bd5f6e6b6e0?w=800&q=80
   https://images.unsplash.com/photo-1611591378425-0b76b5d0786f?w=800&q=80

   - Save as: Footwear1.jpg, Footwear2.jpg, Footwear3.jpg, Footwear4.jpg, Footwear5.jpg, Footwear6.jpg
   - Also save hero background as: hero-bg.jpg

4. ADD MORE PRODUCTS TO SHOP PAGE:
   Copy and paste this template in shop.html inside .products-grid:

   <div class="product-card hidden-product" data-category="category">
       <div class="product-img">
           <img src="images/Footwear1.jpg" alt="Product Name">
           <span class="category-badge">Category</span>
       </div>
       <h3>Product Name</h3>
       <p class="product-desc">Product description</p>
       <p class="price">$199.99</p>
       <a href="https://wa.me/YOUR_NUMBER?text=..." class="btn-buy" target="_blank">
           <i class="fab fa-whatsapp"></i> Buy Now
       </a>
   </div>

   Notes for data-category:
   - Use: men, women, sports, luxury, new
   - Multiple categories: data-category="men luxury"
   - Use "hidden-product" class for Load More to work

5. DEPLOYMENT:
   - Upload ALL files to web hosting
   - Keep folder structure exactly same
   - Test on mobile and desktop
   - Test WhatsApp buttons
   - Test Load More and Filter buttons

✅ TROUBLESHOOTING:
- If Load More not working: Check browser console for errors
- If images not showing: Check image paths and filenames
- If menu not working on mobile: Check JavaScript is loaded
- If WhatsApp not opening: Check number format (no +, no spaces)

===========================================
QUICK START:
1. Change WhatsApp number
2. Add social media links
3. Download images
4. Upload to hosting
5. Test all features
6. Website is live!
===========================================
