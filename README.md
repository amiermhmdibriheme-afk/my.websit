<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>کلینیک دندانپزشکی دکتر ابراهیمی</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Vazirmatn', sans-serif; direction: rtl; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .card-hover { transition: transform 0.3s ease, box-shadow 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 40px rgba(0,0,0,0.1); }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="gradient-bg text-white py-6">
        <div class="container mx-auto px-6">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <div class="bg-white p-3 rounded-full">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.94-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/>
                        </svg>
                    </div>
                    <div>
                        <h1 class="text-2xl font-bold">کلینیک دندانپزشکی دکتر ابراهیمی</h1>
                        <p class="text-blue-100">لبخند شما، اولویت ماست</p>
                    </div>
                </div>
                <button onclick="bookAppointment()" class="bg-white text-blue-600 px-6 py-3 rounded-lg font-semibold hover:bg-blue-50 transition duration-300 shadow-lg">
                    📅 رزرو نوبت
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold text-gray-800 mb-6">به کلینیک برتر دندانپزشکی خوش آمدید</h2>
            <p class="text-xl text-gray-600 mb-8 max-w-3xl mx-auto">
                در کلینیک دندانپزشکی دکتر ابراهیمی، ما خدمات جامع دندانپزشکی را با جدیدترین تکنولوژی 
                و رویکردی ملایم ارائه می‌دهیم تا راحتی و رضایت شما را تضمین کنیم.
            </p>
            <div class="flex justify-center space-x-8 text-center">
                <div class="bg-blue-50 p-6 rounded-lg">
                    <div class="text-3xl mb-2">😊</div>
                    <div class="text-2xl font-bold text-blue-600">۵۰۰+</div>
                    <div class="text-gray-600">بیمار راضی</div>
                </div>
                <div class="bg-green-50 p-6 rounded-lg">
                    <div class="text-3xl mb-2">⭐</div>
                    <div class="text-2xl font-bold text-green-600">۱۵+</div>
                    <div class="text-gray-600">سال تجربه</div>
                </div>
                <div class="bg-purple-50 p-6 rounded-lg">
                    <div class="text-3xl mb-2">🏆</div>
                    <div class="text-2xl font-bold text-purple-600">۱۰۰%</div>
                    <div class="text-gray-600">رضایت مندی</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">خدمات ما</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Filling Service -->
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover">
                    <div class="text-center mb-6">
                        <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">پرکردن دندان</h3>
                        <p class="text-gray-600 leading-relaxed">
                            دندان‌های شما را با پرکردن‌های کامپوزیت و آمالگام با کیفیت بالا ترمیم کنید. 
                            ما از جدیدترین مواد استفاده می‌کنیم تا دوام و ظاهر طبیعی را تضمین کنیم.
                        </p>
                    </div>
                    <ul class="text-sm text-gray-500 space-y-2">
                        <li>✓ پرکردن کامپوزیت (هم‌رنگ دندان)</li>
                        <li>✓ پرکردن آمالگام</li>
                        <li>✓ روش‌های بدون درد</li>
                        <li>✓ نتایج ماندگار</li>
                    </ul>
                </div>

                <!-- Extraction Service -->
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover">
                    <div class="text-center mb-6">
                        <div class="bg-red-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-red-600" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.1 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">کشیدن دندان</h3>
                        <p class="text-gray-600 leading-relaxed">
                            کشیدن دندان ایمن و راحت در صورت نیاز. 
                            ما راحتی شما را با تکنیک‌های مدرن بی‌حسی در اولویت قرار می‌دهیم.
                        </p>
                    </div>
                    <ul class="text-sm text-gray-500 space-y-2">
                        <li>✓ کشیدن ساده</li>
                        <li>✓ کشیدن دندان عقل</li>
                        <li>✓ حداقل ناراحتی</li>
                        <li>✓ راهنمایی پس از درمان</li>
                    </ul>
                </div>

                <!-- Surgery Service -->
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover">
                    <div class="text-center mb-6">
                        <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8 text-green-600" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M19 8h-2v3h-3v2h3v3h2v-3h3v-2h-3V8zM4 8h2V6H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-2h-2v2H4V8zm9-2V4h-2v2H9v2h2v2h2V6h2V4h-2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">جراحی‌های دندانپزشکی</h3>
                        <p class="text-gray-600 leading-relaxed">
                            روش‌های جراحی پیشرفته با دقت و مراقبت انجام می‌شود. 
                            از ایمپلنت تا جراحی‌های پیچیده دهان و دندان.
                        </p>
                    </div>
                    <ul class="text-sm text-gray-500 space-y-2">
                        <li>✓ ایمپلنت دندان</li>
                        <li>✓ جراحی دهان</li>
                        <li>✓ تکنیک‌های پیشرفته</li>
                        <li>✓ مراقبت تخصصی</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">تماس با ما</h2>
            <div class="max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-12">
                    <!-- Contact Info -->
                    <div class="space-y-8">
                        <div class="flex items-center space-x-4">
                            <div class="bg-blue-100 p-3 rounded-full">
                                <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/>
                                </svg>
                            </div>
                            <div>
                                <h3 class="font-semibold text-gray-800">تلفن کلینیک</h3>
                                <p class="text-blue-600 text-lg font-medium">۰۲۱-۱۲۳۴۵۶۷۸</p>
                            </div>
                        </div>

                        <div class="flex items-center space-x-4">
                            <div class="bg-green-100 p-3 rounded-full">
                                <svg class="w-6 h-6 text-green-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M17 4h3c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2h-3V4zm-7 16h3V4h-3v16zm-7 0h3V4H3v16z"/>
                                </svg>
                            </div>
                            <div>
                                <h3 class="font-semibold text-gray-800">شماره همراه</h3>
                                <p class="text-green-600 text-lg font-medium">۰۹۱۵۶۱۴۲۸۷۵</p>
                            </div>
                        </div>

                        <div class="flex items-center space-x-4">
                            <div class="bg-purple-100 p-3 rounded-full">
                                <svg class="w-6 h-6 text-purple-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
                                </svg>
                            </div>
                            <div>
                                <h3 class="font-semibold text-gray-800">آدرس</h3>
                                <p class="text-gray-600">شهرک مهرگان، آسمان ۱۳<br>پلاک ۱۹</p>
                            </div>
                        </div>

                        <div class="bg-blue-50 p-6 rounded-lg">
                            <h3 class="font-semibold text-gray-800 mb-3">ساعات کاری</h3>
                            <div class="space-y-2 text-gray-600">
                                <div class="flex justify-between">
                                    <span>شنبه تا چهارشنبه:</span>
                                    <span>۹:۰۰ تا ۱۸:۰۰</span>
                                </div>
                                <div class="flex justify-between">
                                    <span>پنج‌شنبه:</span>
                                    <span>۹:۰۰ تا ۱۴:۰۰</span>
                                </div>
                                <div class="flex justify-between">
                                    <span>جمعه:</span>
                                    <span>تعطیل</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Appointment Form -->
                    <div class="bg-gray-50 p-8 rounded-xl">
                        <h3 class="text-xl font-semibold text-gray-800 mb-6">رزرو نوبت</h3>
                        <form onsubmit="handleAppointment(event)" class="space-y-4">
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">نام و نام خانوادگی</label>
                                <input type="text" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">شماره تماس</label>
                                <input type="tel" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">نوع خدمت</label>
                                <select required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                                    <option value="">انتخاب کنید</option>
                                    <option value="filling">پرکردن دندان</option>
                                    <option value="extraction">کشیدن دندان</option>
                                    <option value="surgery">جراحی دندانپزشکی</option>
                                    <option value="consultation">مشاوره عمومی</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">تاریخ مورد نظر</label>
                                <input type="date" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            <button type="submit" class="w-full gradient-bg text-white py-3 rounded-lg font-semibold hover:opacity-90 transition duration-300">
                                رزرو نوبت
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <div class="mb-4">
                <h3 class="text-xl font-semibold mb-2">کلینیک دندانپزشکی دکتر ابراهیمی</h3>
                <p class="text-gray-400">ارائه خدمات برتر دندانپزشکی با رویکردی ملایم</p>
            </div>
            <div class="flex justify-center space-x-8 text-sm">
                <span>📞 ۰۲۱-۱۲۳۴۵۶۷۸</span>
                <span>📱 ۰۹۱۵۶۱۴۲۸۷۵</span>
                <span>📧 info@ebrahimidental.com</span>
            </div>
            <div class="mt-6 pt-6 border-t border-gray-700">
                <p class="text-gray-400">&copy; ۱۴۰۳ کلینیک دندانپزشکی دکتر ابراهیمی. تمامی حقوق محفوظ است.</p>
            </div>
        </div>
    </footer>

    <script>
        function bookAppointment() {
            // Scroll to the appointment form
            document.querySelector('form').scrollIntoView({ 
                behavior: 'smooth',
                block: 'center'
            });
            
            // Add a subtle highlight effect
            const form = document.querySelector('.bg-gray-50');
            form.style.boxShadow = '0 0 20px rgba(59, 130, 246, 0.3)';
            setTimeout(() => {
                form.style.boxShadow = '';
            }, 2000);
        }

        function handleAppointment(event) {
            event.preventDefault();
            
            // Get form data
            const formData = new FormData(event.target);
            const name = event.target.querySelector('input[type="text"]').value;
            const phone = event.target.querySelector('input[type="tel"]').value;
            const service = event.target.querySelector('select').value;
            const date = event.target.querySelector('input[type="date"]').value;
            
            // Show success message
            const button = event.target.querySelector('button');
            const originalText = button.textContent;
            
            button.textContent = '✓ نوبت درخواست شد!';
            button.style.backgroundColor = '#10b981';
            
            // Show confirmation alert
            setTimeout(() => {
                alert(`متشکریم ${name}! درخواست نوبت شما برای ${service} در تاریخ ${date} دریافت شد. ما از طریق شماره ${phone} با شما تماس خواهیم گرفت تا زمان نوبت را تأیید کنیم.`);
                
                // Reset form and button
                event.target.reset();
                button.textContent = originalText;
                button.style.backgroundColor = '';
            }, 1000);
        }

        // Add smooth scrolling for better UX
        document.addEventListener('DOMContentLoaded', function() {
            // Add loading animation
            document.body.style.opacity = '0';
            setTimeout(() => {
                document.body.style.transition = 'opacity 0.5s ease';
                document.body.style.opacity = '1';
            }, 100);
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9744dbceb798048f',t:'MTc1NjA1OTU3My4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
