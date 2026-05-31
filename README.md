<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة قبضة الطبية - QMC</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Tajawal', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#0f172a',    // Slate 900
                            darker: '#020617',  // Slate 950
                            card: '#1e293b',    // Slate 800
                            gold: '#fbbf24',    // Amber 400
                            blue: '#1e3a8a',    // Blue 900
                            light: '#f8fafc',   // Slate 50
                        }
                    }
                }
            }
        }
    </script>
    
</head>
<body class="bg-brand-darker text-brand-light antialiased selection:bg-brand-gold selection:text-brand-darker">

    <nav class="fixed w-full z-50 glass-panel border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center gap-3">
                    <div class="h-12 bg-white rounded flex items-center justify-center shadow-lg shadow-brand-gold/20 px-2 py-1">
                        <img src="https://h.top4top.io/p_3797ofypf1.jpg" class="h-full object-contain" onerror="this.onerror=null; this.src='https://via.placeholder.com/120x40/ffffff/1e3a8a?text=QMC+LOGO';">
                    </div>
                    <div>
                        <h1 class="text-xl font-bold text-white tracking-wide">قبضة الطبية</h1>
                        <p class="text-xs text-gray-400 font-sans tracking-widest">QMC MEDICAL</p>
                    </div>
                </div>

                <div class="md:hidden flex items-center">
                    <button onclick="window.print()" class="px-3 py-1.5 flex items-center gap-1.5 text-brand-darker bg-brand-gold border border-brand-gold rounded-md hover:bg-yellow-400 transition font-bold text-sm shadow-md">
                        <i data-lucide="download" class="w-4 h-4"></i>
                        تحميل PDF
                    </button>
                </div>

                <div class="hidden md:block">
                    <div class="flex items-baseline space-x-reverse space-x-6 text-sm font-medium">
                        <a href="#about" class="hover:text-brand-gold transition">عن الشركة</a>
                        <a href="#vision" class="hover:text-brand-gold transition">الرؤية والرسالة</a>
                        <a href="#ceo-message" class="hover:text-brand-gold transition">رسالة الإدارة</a>
                        <a href="#services" class="hover:text-brand-gold transition">الخدمات</a>
                        <a href="#values" class="hover:text-brand-gold transition">معاييرنا</a>
                        
                        <button onclick="window.print()" class="px-4 py-2 flex items-center gap-2 text-brand-gold border border-brand-gold rounded-md hover:bg-brand-gold hover:text-brand-darker transition font-bold" title="طباعة أو حفظ كملف PDF">
                            <i data-lucide="download" class="w-4 h-4"></i>
                            تحميل PDF
                        </button>

                        <a href="#contact" class="px-4 py-2 bg-brand-gold text-brand-darker rounded-md hover:bg-yellow-300 transition font-bold">تواصل معنا</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <section class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden min-h-screen flex items-center">
        <div class="absolute top-0 left-0 w-full h-full overflow-hidden z-0">
            <div class="absolute -top-40 -right-40 w-96 h-96 bg-brand-blue rounded-full mix-blend-multiply filter blur-3xl opacity-30 animate-pulse"></div>
            <div class="absolute top-40 -left-40 w-96 h-96 bg-brand-gold rounded-full mix-blend-multiply filter blur-3xl opacity-10 animate-pulse" style="animation-delay: 2s;"></div>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <span class="inline-block py-1 px-3 rounded-full bg-brand-card border border-gray-700 text-brand-gold text-sm font-semibold mb-6">الملف التعريفي الرسمي 2025</span>
            <h1 class="text-5xl md:text-7xl font-extrabold mb-6 leading-tight">
                شركة <span class="gradient-text">قبضة الطبية</span>
            </h1>
            <h2 class="text-2xl md:text-3xl font-light text-gray-300 mb-8">Qabdah Medical Company (QMC)</h2>
            <p class="mt-4 text-xl md:text-2xl text-gray-400 max-w-3xl mx-auto font-medium">
                شريككم الموثوق في الرعاية الصحية والخدمات الطبية في المملكة العربية السعودية
            </p>
            <div class="mt-10 flex justify-center gap-4">
                <a href="#services" class="px-8 py-3 bg-brand-gold text-brand-darker rounded-lg font-bold text-lg hover:bg-yellow-400 transition shadow-lg shadow-brand-gold/30">استكشف خدماتنا</a>
                <a href="#about" class="px-8 py-3 bg-brand-card text-white border border-gray-700 rounded-lg font-bold text-lg hover:bg-gray-800 transition">من نحن</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-20 bg-brand-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h3 class="text-brand-gold font-bold text-lg mb-2">01 / الهوية والريادة الطبية</h3>
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">خطوتنا الأولى نحو الابتكار.. من نحن؟</h2>
                    <p class="text-gray-300 text-lg leading-relaxed mb-6">
                        تأسست <strong class="text-white">شركة قبضة الطبية</strong> ككيان وطني رائد ومتخصص في قطاع الرعاية الصحية. حيث تعمل برؤية طموحة لتلبية الاحتياجات المتنامية للسوق الطبي في المملكة.
                    </p>
                    <p class="text-gray-300 text-lg leading-relaxed">
                        تمكنا في فترة وجيزة من بناء سمعة راسخة كإحدى الشركات الاعتمادية في مجالات التوريد والتوزيع الطبي، معتمدين على شبكة لوجستية متطورة وفريق عمل احترافي يضع رضى العميل في قمة أولوياته.
                    </p>
                    
                    <div class="mt-8 grid grid-cols-2 gap-4">
                        <div class="bg-brand-card p-4 rounded-lg border border-gray-800 flex items-center gap-4">
                            <i data-lucide="shield-check" class="text-brand-gold w-8 h-8"></i>
                            <div>
                                <h4 class="font-bold text-white">معتمدة وموثوقة</h4>
                                <p class="text-xs text-gray-400">تراخيص محلية وعالمية</p>
                            </div>
                        </div>
                        <div class="bg-brand-card p-4 rounded-lg border border-gray-800 flex items-center gap-4">
                            <i data-lucide="truck" class="text-brand-gold w-8 h-8"></i>
                            <div>
                                <h4 class="font-bold text-white">تغطية شاملة</h4>
                                <p class="text-xs text-gray-400">جميع مناطق المملكة</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="relative mt-12 lg:mt-0">
                    <div class="aspect-[3/4] md:aspect-[4/3] bg-gradient-to-tr from-brand-blue to-brand-card rounded-2xl p-2 shadow-2xl">
                        <div class="w-full h-full bg-brand-darker rounded-xl border border-gray-700 overflow-hidden">
                             <div class="grid grid-cols-2 md:grid-cols-4 grid-rows-4 md:grid-rows-2 h-full gap-1.5 p-1.5">
                                
                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://images.unsplash.com/photo-1586773860418-d37222d8fce3?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="مستودعات طبية" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>
                                
                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://images.unsplash.com/photo-1581594693702-fbdc51b2763b?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="معدات طبية" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>
                                
                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://a.top4top.io/p_3803nizsr1.jpeg" alt="أدوية" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>
                                
                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://images.unsplash.com/photo-1631549916768-4119b2e5f926?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="مرافق صحية" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>

                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="مختبرات" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>

                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://f.top4top.io/p_3803wjn311.jpeg" alt="غرف عمليات" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>

                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://images.unsplash.com/photo-1584982751601-97dcc096659c?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="مستلزمات طبية" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>

                                <div class="overflow-hidden rounded-md group relative">
                                    <div class="absolute inset-0 bg-brand-darker/40 group-hover:bg-transparent transition duration-300 z-10"></div>
                                    <img src="https://b.top4top.io/p_3803sq4722.jpeg" alt="علاجات" class="w-full h-full object-cover transform group-hover:scale-110 transition duration-500">
                                </div>

                             </div>
                        </div>
                    </div>
                    <div class="absolute -bottom-6 -right-6 w-20 h-20 bg-brand-gold rounded-full flex items-center justify-center shadow-lg border-4 border-brand-dark hover:scale-110 transition duration-300">
                        <i data-lucide="microscope" class="w-10 h-10 text-brand-darker"></i>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="vision" class="py-20 bg-brand-darker relative border-y border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="glass-panel p-10 rounded-2xl relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-2 h-full bg-brand-gold"></div>
                    <i data-lucide="eye" class="w-12 h-12 text-brand-gold mb-6 group-hover:scale-110 transition duration-300"></i>
                    <h3 class="text-2xl font-bold mb-4">رؤيتنا</h3>
                    <p class="text-gray-300 text-lg leading-relaxed">
                        أن نكون الخيار الأول والأساسي للمستشفيات والمراكز الطبية في قطاع التوريد الطبي على مستوى المملكة، والاسم الأكثر موثوقية في تمثيل الوكالات العالمية.
                    </p>
                </div>
                <div class="glass-panel p-10 rounded-2xl relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-2 h-full bg-blue-500"></div>
                    <i data-lucide="target" class="w-12 h-12 text-blue-500 mb-6 group-hover:scale-110 transition duration-300"></i>
                    <h3 class="text-2xl font-bold mb-4">رسالتنا</h3>
                    <p class="text-gray-300 text-lg leading-relaxed">
                        الارتقاء بجودة الخدمات الطبية المقدمة للمجتمع من خلال تأمين أحدث الأدوية، المحاليل والمستلزمات الطبية بكفاءة عالية، مع الالتزام الصارم بأعلى المعايير والمواصفات العالمية والمحلية.
                    </p>
                </div>
            </div>
        </div>
    </section>

   <!-- CEO Message Section -->
    <section id="ceo-message" class="py-16 bg-brand-darker relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-panel p-8 md:p-12 rounded-3xl border border-gray-800 relative overflow-hidden shadow-2xl">
                <!-- تأثير لوني في الخلفية -->
                <div class="absolute -top-24 -left-24 w-64 h-64 bg-brand-gold rounded-full mix-blend-multiply filter blur-3xl opacity-5"></div>

                <div class="grid grid-cols-1 md:grid-cols-12 gap-10 items-center relative z-10">
                    <!-- صورة المدير التنفيذي -->
                    <div class="md:col-span-5 lg:col-span-4">
                        <div class="relative group">
                            <!-- إطار خلفي زينة -->
                            <div class="absolute inset-0 bg-brand-gold rounded-2xl transform -rotate-3 group-hover:-rotate-6 transition duration-500 opacity-70"></div>
                            <!-- الصورة المرفقة للمدير العام التنفيذي -->
                            <img src="https://h.top4top.io/p_380378i671.jpeg" alt="سعيد محمد جمعان الزهراني - المدير العام التنفيذي" class="relative z-10 w-full h-auto aspect-[4/5] object-cover rounded-2xl shadow-xl border border-gray-700">
                        </div>
                    </div>

                    <!-- نص الكلمة -->
                    <div class="md:col-span-7 lg:col-span-8">
                        <div class="flex items-center gap-3 mb-4">
                            <div class="w-12 h-1 bg-brand-gold rounded-full"></div>
                            <h3 class="text-brand-gold font-bold text-lg">رسالة الإدارة</h3>
                        </div>
                        <h2 class="text-3xl md:text-4xl font-bold mb-8 text-white leading-tight">
                            "نلتزم بالريادة في تقديم أفضل معايير الرعاية الصحية لمجتمعنا"
                        </h2>

                        <div class="relative">
                            <!-- أيقونة اقتباس -->
                            <i data-lucide="quote" class="absolute -top-4 -right-4 w-12 h-12 text-gray-700 opacity-50 rotate-180"></i>
                            
                            <!-- مساحة الكلمة -->
                            <div class="relative z-10 border-r-4 border-brand-gold bg-gradient-to-l from-brand-card/80 to-transparent pr-6 pl-4 py-6 rounded-l-xl mb-8">
                                <p class="text-gray-300 text-lg leading-relaxed">
                                 منذ تأسيس شركة قبضة الطبية، وضعنا نصب أعيننا هدفاً واحداً وهو الارتقاء بجودة القطاع الصحي في المملكة. نحن لا نكتفي بكوننا مورداً طبياً، بل نعتبر أنفسنا شركاء استراتيجيين لنجاح المنظومة الصحية. من خلال الالتزام بأعلى معايير الجودة والموثوقية، نسعى لنكون جزءاً فاعلاً في تحقيق مستهدفات رؤية 2030 لقطاع صحي مستدام
                                </p>
                            </div>
                        </div>

                        <!-- اسم المدير التنفيذي -->
                        <div class="flex items-center gap-4">
                            <div>
                                <h4 class="text-2xl font-bold text-white mb-1">سعيد محمد جمعان الزهراني</h4>
                                <p class="text-brand-gold font-medium text-sm">المدير العام التنفيذي - شركة قبضة الطبية</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-20 bg-brand-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h3 class="text-brand-gold font-bold text-lg mb-2">02 / الخدمات الطبية</h3>
                <h2 class="text-3xl md:text-5xl font-bold">مجالات التوريد وقطاعات العمل</h2>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-brand-card p-8 rounded-xl border border-gray-700 hover:border-brand-gold transition duration-300 hover:-translate-y-2">
                    <div class="w-14 h-14 bg-brand-darker rounded-full flex items-center justify-center mb-6 text-brand-gold border border-gray-600">
                        <i data-lucide="pill"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">الأدوية والمستحضرات الطبية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">نقوم بتوريد وتوزيع باقة واسعة من الأدوية الأساسية والنوعية مع الالتزام التام بالاشتراطات الصحية الصارمة.</p>
                    <span class="text-xs font-bold text-brand-gold bg-brand-gold/10 px-2 py-1 rounded">توريد فوري</span>
                </div>

                <div class="bg-brand-card p-8 rounded-xl border border-gray-700 hover:border-brand-gold transition duration-300 hover:-translate-y-2">
                    <div class="w-14 h-14 bg-brand-darker rounded-full flex items-center justify-center mb-6 text-brand-gold border border-gray-600">
                        <i data-lucide="flask-conical"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">المحاليل الطبية والوريدية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">تمتلك شبكة توريد متكاملة لتوفير المحاليل الوريدية والمغذية التي تشكل العصب الأساسي لغرف العمليات والطوارئ.</p>
                    <span class="text-xs font-bold text-brand-gold bg-brand-gold/10 px-2 py-1 rounded">قطاع متميز</span>
                </div>

                <div class="bg-brand-card p-8 rounded-xl border border-gray-700 hover:border-brand-gold transition duration-300 hover:-translate-y-2">
                    <div class="w-14 h-14 bg-brand-darker rounded-full flex items-center justify-center mb-6 text-brand-gold border border-gray-600">
                        <i data-lucide="stethoscope"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">المستلزمات والأدوات الطبية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">تأمين شامل لكافة مستهلكات الأقسام الطبية من أدوات جراحية ومعدات الفحص اليومي والتمريض بالمستشفيات.</p>
                    <span class="text-xs font-bold text-brand-gold bg-brand-gold/10 px-2 py-1 rounded">جودة معتمدة</span>
                </div>

                <div class="bg-brand-card p-8 rounded-xl border border-gray-700 hover:border-brand-gold transition duration-300 hover:-translate-y-2">
                    <div class="w-14 h-14 bg-brand-darker rounded-full flex items-center justify-center mb-6 text-brand-gold border border-gray-600">
                        <i data-lucide="globe"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">إدارة الوكالات الحصرية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">تمثيل حصري وموثوق لأهم الماركات والمصانع الإقليمية والدولية لدخول آمن وفاعل للسوق السعودي.</p>
                    <span class="text-xs font-bold text-brand-gold bg-brand-gold/10 px-2 py-1 rounded">شراكات عالمية</span>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <p class="text-xl font-bold text-gray-300">جودة التوريد من <span class="text-brand-gold">قبضة الطبية</span> يعني الاستقرار المستمر للمشافي والمختبرات.</p>
            </div>
        </div>
    </section>

    <section id="values" class="py-20 bg-brand-darker border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h3 class="text-brand-gold font-bold text-lg mb-2">03 / معايير العمل</h3>
                <h2 class="text-3xl md:text-5xl font-bold mb-4">القيم الجوهرية وعوامل النجاح</h2>
                <p class="text-xl text-gray-400">لماذا نعتبر أنفسنا شركاء لا غنى عنهم؟</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div class="p-6">
                    <div class="w-20 h-20 mx-auto bg-brand-card rounded-2xl flex items-center justify-center mb-6 border-2 border-brand-gold rotate-45 shadow-lg shadow-brand-gold/10">
                        <i data-lucide="shield-alert" class="w-10 h-10 text-brand-gold -rotate-45"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">الجودة والأمان المطلق</h3>
                    <p class="text-gray-400 leading-relaxed">نضمن حفظ وتوريد المواد الطبية في بيئات خاضعة لأدق ظروف الرقابة والبرودة العلاجية لضمان سلامة الاستخدام.</p>
                </div>

                <div class="p-6">
                    <div class="w-20 h-20 mx-auto bg-brand-card rounded-2xl flex items-center justify-center mb-6 border-2 border-brand-gold rotate-45 shadow-lg shadow-brand-gold/10">
                        <i data-lucide="clock" class="w-10 h-10 text-brand-gold -rotate-45"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">الالتزام التام بالمواعيد</h3>
                    <p class="text-gray-400 leading-relaxed">ندرك أن حياة المرضى وخطط المستشفيات مرتبطة بدقة التوريد، لذا نلتزم بتوقيتات حازمة لا تقبل التأخير.</p>
                </div>

                <div class="p-6">
                    <div class="w-20 h-20 mx-auto bg-brand-card rounded-2xl flex items-center justify-center mb-6 border-2 border-brand-gold rotate-45 shadow-lg shadow-brand-gold/10">
                        <i data-lucide="handshake" class="w-10 h-10 text-brand-gold -rotate-45"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">الشراكة الاستراتيجية</h3>
                    <p class="text-gray-400 leading-relaxed">نبني جسور تواصل وشراكة طويلة المدى لتقديم حلول مستدامة ومدروسة لجميع عملائنا في القطاع الصحي.</p>
                </div>
            </div>

            <div class="mt-16 glass-panel rounded-full py-4 px-8 text-center max-w-3xl mx-auto border border-gray-700">
                <p class="text-lg font-bold tracking-wider text-gray-200 flex justify-center items-center gap-4 flex-wrap">
                    <span>جودة</span>
                    <span class="text-brand-gold">•</span>
                    <span>سلامة</span>
                    <span class="text-brand-gold">•</span>
                    <span>أمان</span>
                    <span class="text-brand-gold">•</span>
                    <span>التزام في توريد مستهلكات الرعاية الطبية</span>
                </p>
            </div>
        </div>
    </section>

    <!-- Structure & Partners -->
    <section class="py-20 bg-brand-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
                <!-- Structure -->
                <div>
                    <h3 class="text-brand-gold font-bold text-lg mb-2">04 / الهيكل الإداري</h3>
                    <h2 class="text-3xl font-bold mb-8">أقسام الشركة المتخصصة</h2>
                    
                    <div class="space-y-4">
                        <div class="bg-brand-card p-4 rounded-lg border-r-4 border-brand-gold flex items-center gap-4">
                            <i data-lucide="boxes" class="text-gray-400"></i>
                            <span class="font-bold text-lg">إدارة التوريد والمشتريات الطبية</span>
                        </div>
                        <div class="bg-brand-card p-4 rounded-lg border-r-4 border-brand-gold flex items-center gap-4">
                            <i data-lucide="microscope" class="text-gray-400"></i>
                            <span class="font-bold text-lg">إدارة الجودة والرقابة الدوائية</span>
                        </div>
                        <div class="bg-brand-card p-4 rounded-lg border-r-4 border-brand-gold flex items-center gap-4">
                            <i data-lucide="file-text" class="text-gray-400"></i>
                            <span class="font-bold text-lg">إدارة المبيعات والمناقصات الحكومية</span>
                        </div>
                        <div class="bg-brand-card p-4 rounded-lg border-r-4 border-brand-gold flex items-center gap-4">
                            <i data-lucide="truck" class="text-gray-400"></i>
                            <span class="font-bold text-lg">إدارة النقل اللوجستي وسلسلة التبريد</span>
                        </div>
                    </div>
                </div>

                <!-- Partners -->
                <div>
                    <h3 class="text-brand-gold font-bold text-lg mb-2">05 / شركاء النجاح</h3>
                    <h2 class="text-3xl font-bold mb-8">نعتز بثقتهم</h2>
                    
                    <!-- تم تعديل الشبكة لتكون 4 أعمدة (sm:grid-cols-4) لتستوعب 8 شركاء بشكل مرتب -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-4">
                        <!-- Partner 1 -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://i0.wp.com/ksalogo.com/wp-content/uploads/2025/10/Minisrty-of-Health.png?fit=1000%2C1000&ssl=1" alt="وزارة الصحة" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 2 -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://salogos.b-cdn.net/logos/svg/1774895664426-hfqfkwsj.svg" alt="هيئة الغذاء والدواء" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 3 -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://i0.wp.com/ksalogo.com/wp-content/uploads/2025/01/Nupco.png?fit=1000%2C1000&ssl=1" alt="المستشفيات الحكومية" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 4 -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://cdn.salla.sa/AnWnb/y8fTcSUzD2T1C7TBcQEUYyBRNbiHxjRI3Gjptrkf.jpg" alt="الوكالات الطبية" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 5 -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://b.top4top.io/p_3803glmug2.jpeg" alt="الوكالات الطبية" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 6 -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://c.top4top.io/p_3803r8sik3.jpeg" alt="المراكز الطبية الخاصة" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 7 (مكان جديد) -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://d.top4top.io/p_3803anqob4.jpeg" alt="مكان لشريك جديد" class="max-h-full max-w-full object-contain">
                        </div>
                        <!-- Partner 8 (مكان جديد) -->
                        <div class="bg-white h-24 sm:h-28 rounded-xl flex items-center justify-center p-3 shadow-lg hover:shadow-brand-gold/30 transition-all duration-300 hover:-translate-y-1 cursor-pointer">
                            <img src="https://e.top4top.io/p_3803483qa5.jpeg" alt="مكان لشريك جديد" class="max-h-full max-w-full object-contain">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-brand-darker relative border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center bg-brand-card rounded-3xl p-8 md:p-12 border border-gray-700 shadow-2xl">
                <div>
                    <h3 class="text-brand-gold font-bold text-lg mb-2">06 / تواصل معنا</h3>
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">بناء شراكات مستدامة</h2>
                    <p class="text-gray-300 text-lg mb-8 leading-relaxed">
                        مكتب الإدارة التنفيذية يسره تواصلكم وخدمتكم على الدوام.<br>
                        فريق التوريد وتجربة العملاء لدينا جاهز لاستقبال الطلبات، إعداد المناقصات الطبية، وتوقيع اتفاقيات الوكالات والتوزيع على مستوى مناطق المملكة.
                    </p>
                    
                    <div class="space-y-6">
                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-brand-darker rounded-full flex items-center justify-center text-brand-gold border border-gray-600">
                                <i data-lucide="phone"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">الجوال الفوري والتواصل</p>
                                <p class="text-xl font-bold" dir="ltr">054 545 1555</p>
                            </div>
                        </div>
                        
                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-brand-darker rounded-full flex items-center justify-center text-brand-gold border border-gray-600">
                                <i data-lucide="mail"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">البريد الإلكتروني للرئيس التنفيذي</p>
                                <p class="text-lg font-bold">ceo@medical-grip.com</p>
                            </div>
                        </div>

                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-brand-darker rounded-full flex items-center justify-center text-brand-gold border border-gray-600">
                                <i data-lucide="globe"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">الموقع الإلكتروني الرسمي</p>
                                <p class="text-lg font-bold">https://medical-grip.com/</p>
                            </div>
                        </div>

                        <div class="flex items-center gap-4">
                            <div class="w-12 h-12 bg-brand-darker rounded-full flex items-center justify-center text-brand-gold border border-gray-600">
                                <i data-lucide="map-pin"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">المقر الرئيسي</p>
                                <p class="text-lg font-bold">المملكة العربية السعودية</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="flex flex-col items-center justify-center p-8 bg-brand-darker rounded-2xl border border-gray-700 h-full">
                    <div class="w-48 h-48 bg-white p-2 rounded-xl mb-6 shadow-lg shadow-white/5 flex items-center justify-center">
                        <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=http://www.medical-grip.com" alt="QR Code" class="w-full h-full object-cover rounded-lg">
                    </div>
                    <p class="text-gray-400 text-center mb-4">امسح الرمز لزيارة موقعنا الإلكتروني</p>
                    <a href="http://www.medical-grip.com" target="_blank" class="text-brand-gold font-bold hover:underline flex items-center gap-2">
                        <span>زيارة الموقع</span>
                        <i data-lucide="external-link" class="w-4 h-4"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-brand-darker border-t border-gray-800 py-8 text-center">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex items-center justify-center gap-3 mb-4">
                <div class="h-10 bg-white rounded flex items-center justify-center px-2 py-1">
                    <img src="https://h.top4top.io/p_3797ofypf1.jpg" alt="شعار شركة قبضة الطبية" class="h-full object-contain" onerror="this.onerror=null; this.src='https://via.placeholder.com/120x40/ffffff/1e3a8a?text=QMC+LOGO';">
                </div>
                <span class="text-xl font-bold text-white tracking-wide">شركة قبضة الطبية</span>
            </div>
            <p class="text-gray-500 text-sm">
                &copy; 2025 شركة قبضة الطبية (QMC) - جميع الحقوق محفوظة. 
            </p>
            <p class="text-gray-600 text-xs mt-2">
                شريككم الموثوق في الرعاية والخدمات الطبية - المملكة العربية السعودية
            </p>
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();
    </script>
</body>
</html>
