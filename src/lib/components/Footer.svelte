<footer class="bg-bg-light pb-20 px-6 text-black">
  <div class="max-w-[1400px] mx-auto">
    
    <!-- Big Bland Logo with Pattern -->
    <div class="w-full mb-20 overflow-hidden">
       <!-- SVG representation of the BLAND logo with pixel pattern -->
       <svg viewBox="0 0 1200 300" class="w-full h-auto">
          <defs>
             <pattern id="pixelPattern" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                <rect x="0" y="0" width="10" height="10" fill="#E83B36" />
                <rect x="10" y="0" width="10" height="10" fill="#000000" />
                <rect x="0" y="10" width="10" height="10" fill="#F3F3EF" />
                <rect x="10" y="10" width="10" height="10" fill="#8B229D" />
                <!-- Randomize colors a bit more to look like noise -->
                <rect x="2" y="2" width="6" height="6" fill="#FFA500" />
                <rect x="12" y="12" width="6" height="6" fill="#FFFF00" />
             </pattern>
             <mask id="textMask">
                <text x="50%" y="50%" dy=".35em" text-anchor="middle" font-weight="900" font-size="300" font-family="sans-serif" fill="white">bland</text>
             </mask>
          </defs>
          
          <!-- Background black for text -->
          <rect width="100%" height="100%" fill="black" mask="url(#textMask)" />
          
          <!-- Pixel pattern overlay masked by text - actually the screenshot shows the text IS the pattern mask, or the text is filled with pattern. 
               Let's try filling text with pattern. -->
          <text x="50%" y="50%" dy=".35em" text-anchor="middle" font-weight="900" font-size="350" font-family="sans-serif" fill="url(#pixelPattern)" letter-spacing="-20">bland</text>
       </svg>
    </div>

    <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-12 mb-20">
       
       <!-- Industries -->
       <div>
          <h4 class="font-bold mb-6">Industries</h4>
          <ul class="space-y-3 text-sm text-gray-600">
             <li><a href="#" class="hover:text-black">Hospitality</a></li>
             <li><a href="#" class="hover:text-black">Financial Services</a></li>
             <li><a href="#" class="hover:text-black">Healthcare</a></li>
             <li><a href="#" class="hover:text-black">Real Estate</a></li>
             <li><a href="#" class="hover:text-black">Logistics</a></li>
             <li><a href="#" class="hover:text-black">Small Business</a></li>
             <li><a href="#" class="hover:text-black">Enterprise</a></li>
          </ul>
       </div>

       <!-- Use Cases -->
       <div>
          <h4 class="font-bold mb-6">Use Cases</h4>
          <ul class="space-y-3 text-sm text-gray-600">
             <li><a href="#" class="hover:text-black">Appointment Booking</a></li>
             <li><a href="#" class="hover:text-black">Financial Intake</a></li>
             <li><a href="#" class="hover:text-black">Logistics ID Verification</a></li>
             <li><a href="#" class="hover:text-black">Customer Service</a></li>
             <li><a href="#" class="hover:text-black">Lead Qualification</a></li>
             <li><a href="#" class="hover:text-black">Survey</a></li>
          </ul>
       </div>

       <!-- Case Studies -->
       <div>
          <h4 class="font-bold mb-6">Case Studies</h4>
          <ul class="space-y-3 text-sm text-gray-600">
             <li><a href="#" class="hover:text-black">Parade</a></li>
             <li><a href="#" class="hover:text-black">MonsterRG</a></li>
             <li><a href="#" class="hover:text-black">Slash</a></li>
             <li><a href="#" class="hover:text-black">Kin Insurance</a></li>
             <li><a href="#" class="hover:text-black">PrecisionIT</a></li>
             <li><a href="#" class="hover:text-black">Tipalti</a></li>
             <li><a href="#" class="hover:text-black">Bilt</a></li>
          </ul>
       </div>

       <!-- Resources -->
       <div>
          <h4 class="font-bold mb-6">Resources</h4>
          <ul class="space-y-3 text-sm text-gray-600">
             <li><a href="#" class="hover:text-black">Blog</a></li>
             <li><a href="#" class="hover:text-black">Docs</a></li>
             <li><a href="#" class="hover:text-black">Careers</a></li>
             <li><a href="#" class="hover:text-black">Trust & Security</a></li>
             <li><a href="#" class="hover:text-black">No Code University</a></li>
             <li><a href="#" class="hover:text-black">Community</a></li>
             <li><a href="#" class="hover:text-black">Help Center</a></li>
          </ul>
       </div>

       <!-- Support -->
       <div>
          <h4 class="font-bold mb-6">Support</h4>
          <ul class="space-y-3 text-sm text-gray-600">
             <li><a href="#" class="hover:text-black">Privacy Policy</a></li>
             <li><a href="#" class="hover:text-black">Terms</a></li>
             <li><a href="#" class="hover:text-black">Cookie Policy</a></li>
             <li><a href="#" class="hover:text-black">Trust & Security</a></li>
             <li><a href="#" class="hover:text-black">Sub-processor List</a></li>
             <li><a href="#" class="hover:text-black">Data Processing Agreement</a></li>
             <li><a href="#" class="hover:text-black">Model Governance</a></li>
          </ul>
       </div>

    </div>

    <!-- Badges -->
    <div class="flex justify-center gap-6 mb-12">
       <div class="w-16 h-16 rounded-full bg-black text-white flex flex-col items-center justify-center text-[8px] font-bold border-4 border-gray-800">
          <span>SOC 2</span>
          <span class="text-[6px] font-normal">Type II</span>
       </div>
       <div class="w-16 h-16 rounded-full bg-black text-white flex flex-col items-center justify-center text-[8px] font-bold border-4 border-gray-800">
          <span>HIPAA</span>
          <span class="text-[6px] font-normal">Compliant</span>
       </div>
       <div class="w-16 h-16 rounded-full bg-black text-white flex flex-col items-center justify-center text-[8px] font-bold border-4 border-gray-800">
          <span>GDPR</span>
          <span class="text-[6px] font-normal">Compliant</span>
       </div>
    </div>

    <!-- Bottom -->
    <div class="flex flex-col items-center gap-4 text-xs text-gray-500">
       <a href="#" class="hover:text-black">Cookie Settings</a>
       <div>Bland.AI, Inc. © 2025</div>
    </div>

  </div>
</footer>