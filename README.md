EN: HOUROUS-MAC is a specialized networking utility developed by BX2 for Kali Linux environments. It leverages low-level system calls to manipulate the Media Access Control (MAC) address of network interfaces. By decoupling the hardware's physical identity from the logical network layer, it provides an essential layer of anonymity during penetration testing and security audits.
​AR: أداة HOUROUS-MAC هي وسيلة تقنية متطورة طورها BX2 لبيئات كالي لينكس. تعتمد الأداة على استدعاءات النظام (System Calls) للتحكم في عنوان الـ MAC الخاص بواجهات الشبكة. من خلال فصل الهوية الفيزيائية للجهاز عن طبقة الشبكة المنطقية، توفر الأداة طبقة أساسية من التخفي أثناء عمليات اختبار الاختراق والتدقيق الأمني.
​🧪 Scientific Concept / المبدأ العلمي
​EN: The tool operates at Layer 2 (Data Link Layer) of the OSI Model. It temporarily overrides the Burned-In Address (BIA) in the kernel's network stack using the AF_PACKET socket interface. This prevents tracking by APs (Access Points) and bypasses MAC-based filtering systems without altering the hardware's permanent ROM.
​AR: تعمل الأداة في الطبقة الثانية (Data Link Layer) من نموذج OSI. تقوم الأداة بتجاوز العنوان المحروق (BIA) برمجياً في ذاكرة النواة (Kernel) باستخدام واجهة AF_PACKET. هذا يمنع تتبع الجهاز من قبل نقاط الوصول (APs) ويتجاوز أنظمة الفلترة المبنية على الماك أدريس دون تغيير الـ ROM الأصلي للبطاقة.
​✨ Features / المميزات
​Stealth Mode: Instant identity rotation.
​Randomization: Generate valid OUI (Organizationally Unique Identifier) compliant addresses.
​Zero Trace: Resets to original hardware ID after reboot.
​Professional UI: Clean ASCII art interface (The Eye of Horus).
