<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strategy 4: Equipment Rental Programs - COMPLETE</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: #333; background: linear-gradient(135deg, #9b59b6, #8e44ad); padding: 20px; }
        .container { max-width: 1400px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .language-toggle { position: sticky; top: 20px; z-index: 1000; background: rgba(255,255,255,0.98); padding: 15px 40px; display: flex; justify-content: center; gap: 15px; border-bottom: 3px solid #9b59b6; }
        .lang-btn { padding: 12px 30px; border: 2px solid #9b59b6; background: white; color: #9b59b6; border-radius: 8px; cursor: pointer; font-size: 1.1em; font-weight: bold; }
        .lang-btn.active { background: #9b59b6; color: white; }
        .header { background: linear-gradient(135deg, #8e44ad, #9b59b6); color: white; padding: 60px 40px; text-align: center; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .section-title { font-size: 2.5em; color: #8e44ad; margin-bottom: 30px; text-align: center; border-bottom: 4px solid #9b59b6; padding-bottom: 15px; }
        .product-card { background: #f3e5f5; padding: 20px; border-radius: 10px; border-left: 4px solid #9b59b6; margin: 15px 0; }
        .revenue-box { background: linear-gradient(135deg, #8e44ad, #9b59b6); color: white; padding: 30px; border-radius: 15px; text-align: center; margin: 25px 0; }
        .revenue-amount { font-size: 3em; font-weight: bold; margin: 15px 0; }
        .stat-box { background: linear-gradient(135deg, #8e44ad, #9b59b6); color: white; padding: 30px; border-radius: 15px; text-align: center; }
        .stat-number { font-size: 3em; font-weight: bold; margin-bottom: 10px; }
        ul.benefits { list-style: none; padding: 0; }
        ul.benefits li { padding: 12px; margin: 8px 0; background: #f3e5f5; border-radius: 6px; border-left: 4px solid #9b59b6; }
        ul.benefits li::before { content: '✓ '; color: #27ae60; font-weight: bold; margin-right: 10px; }
        .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 30px 0; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <!-- ENGLISH -->
        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>🔄 STRATEGY 4: Equipment Rental Programs</h1>
                <p style="font-size: 1.4em;">Short-Term Medical Equipment Rental with High Recurring Revenue</p>
                <p style="font-size: 1.2em; margin-top: 15px;">Licensed DME Rentals (80-85%) + Rental Accessories (15-20%)</p>
            </div>

            <div class="section">
                <h2 class="section-title">💰 Revenue Model</h2>
                <div class="revenue-box">
                    <h4 style="font-size: 1.8em;">Year 1 Revenue Target</h4>
                    <span class="revenue-amount">$600K - $1.1M</span>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; text-align: left;">
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>DME Equipment Rentals</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$500K-$900K</p>
                            <p>80-85% from BOC-licensed equipment rentals</p>
                        </div>
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Rental Accessories</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$100K-$200K</p>
                            <p>15-20% from disposables and add-ons</p>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">Monthly</span><span>Recurring Revenue</span></div>
                    <div class="stat-box"><span class="stat-number">60-75%</span><span>Gross Margins</span></div>
                    <div class="stat-box"><span class="stat-number">Insurance</span><span>Medicare Coverage</span></div>
                    <div class="stat-box"><span class="stat-number">3-6 mo</span><span>Average Rental Term</span></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🏥 PRIMARY RENTAL EQUIPMENT (80-85%)</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <h4>🛏️ Hospital Beds (DM11)</h4>
                        <p><strong>Rental Items:</strong> Semi-electric hospital beds, full-electric beds, low beds for fall risk, bariatric beds</p>
                        <p style="margin: 10px 0;"><strong>Monthly Rental:</strong> $150-$400/month</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $120K-$250K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Rent:</strong> Post-surgery recovery (hip/knee replacement 3-6 months), hospice care, temporary illness. Most rentals are 3-6 months. Insurance often covers rental.</p>
                    </div>

                    <div class="product-card">
                        <h4>♿ Wheelchairs & Scooters (M06/M07)</h4>
                        <p><strong>Rental Items:</strong> Manual wheelchairs, power wheelchairs, mobility scooters, transport chairs</p>
                        <p style="margin: 10px 0;"><strong>Monthly Rental:</strong> $50-$300/month</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $100K-$200K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Rent:</strong> Temporary mobility needs post-surgery, trial before purchase, visitors with mobility issues, event/venue accessibility.</p>
                    </div>

                    <div class="product-card">
                        <h4>🩺 Patient Lifts (DM21/DM22)</h4>
                        <p><strong>Rental Items:</strong> Hoyer lifts (portable floor), ceiling lifts, sit-to-stand lifts, sling sets</p>
                        <p style="margin: 10px 0;"><strong>Monthly Rental:</strong> $200-$500/month</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $80K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Rent:</strong> Short-term patient transfers, post-stroke recovery, hospice care, determining need before $3-5K purchase.</p>
                    </div>

                    <div class="product-card">
                        <h4>💨 Oxygen Concentrators (DM28/DM29)</h4>
                        <p><strong>Rental Items:</strong> Stationary concentrators (5-10L), portable concentrators, oxygen cylinders, backup systems</p>
                        <p style="margin: 10px 0;"><strong>Monthly Rental:</strong> $100-$400/month</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $80K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Rent:</strong> Pneumonia recovery, COPD flare-ups, post-surgery oxygen needs, high-altitude travel. Many temporary respiratory needs.</p>
                    </div>

                    <div class="product-card">
                        <h4>🛌 Pressure Relief Mattresses (DM16)</h4>
                        <p><strong>Rental Items:</strong> Alternating pressure mattresses, low air loss systems, foam overlays, therapeutic mattresses</p>
                        <p style="margin: 10px 0;"><strong>Monthly Rental:</strong> $150-$600/month</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $60K-$150K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Rent:</strong> Pressure ulcer treatment, post-surgical healing, temporary bed rest, trial expensive system before purchase.</p>
                    </div>

                    <div class="product-card">
                        <h4>🚿 Bathroom Safety Equipment (DM02)</h4>
                        <p><strong>Rental Items:</strong> Tub transfer benches, shower chairs, commode chairs, bath lifts</p>
                        <p style="margin: 10px 0;"><strong>Monthly Rental:</strong> $30-$150/month</p>
                        <p style="color: #27ae60; font-weight: bold;">Est. Annual Revenue: $40K-$100K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Why Rent:</strong> Hip/knee replacement recovery (2-4 month need), temporary mobility restrictions, elderly visitors staying temporarily.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📦 RENTAL ACCESSORIES (15-20%)</h2>
                <div class="product-card">
                    <h3 style="color: #8e44ad;">Mandatory Disposables & Add-Ons</h3>
                    <ul class="benefits">
                        <li><strong>Hospital Bed Accessories:</strong> Sheets/linens (patient keeps), bed rails and positioning aids, overbed tables, IV poles</li>
                        <li><strong>Wheelchair/Scooter Add-Ons:</strong> Cushions (patient purchases), cup holders and bags, weather protection, safety accessories</li>
                        <li><strong>Patient Lift Accessories:</strong> Sling sets (multiple for washing), disposable sling liners, positioning accessories</li>
                        <li><strong>Oxygen Supplies:</strong> Cannulas and tubing (disposable), humidifier bottles, oxygen conserving devices</li>
                        <li><strong>Mattress Accessories:</strong> Disposable mattress covers, pump filters, protective sheets</li>
                        <li><strong>Bathroom Safety Add-Ons:</strong> Non-slip mats, bath cushions, handheld shower heads</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Est. Annual Revenue: $100K-$200K</p>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Business Model Advantages</h2>
                <div class="product-card">
                    <h3>Why Rental Programs Are Highly Profitable:</h3>
                    <ul class="benefits">
                        <li><strong>Recurring Monthly Revenue:</strong> Predictable cash flow from monthly rentals, average 3-6 month rental periods, some long-term rentals continue years</li>
                        <li><strong>Equipment ROI:</strong> Hospital bed costs $1,000, rents for $200/month = 5 month payback, after 5 months pure profit for years of continued use</li>
                        <li><strong>Insurance Reimbursement:</strong> Medicare/Medicaid covers most rental equipment, insurance handles billing complexity, reduces collection issues</li>
                        <li><strong>Maintenance Revenue:</strong> Monthly service fees, repair charges, upgrade opportunities, replacement accessories</li>
                        <li><strong>Purchase Conversion:</strong> 20-30% of renters convert to purchase, rent-to-own programs, credit rental payments toward purchase</li>
                        <li><strong>Asset Utilization:</strong> Equipment rented 60-80% of time, each unit generates revenue multiple times, depreciation spreads across many rentals</li>
                    </ul>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">5-8 mo</span><span>Equipment Payback</span></div>
                    <div class="stat-box"><span class="stat-number">3-5 yrs</span><span>Equipment Lifespan</span></div>
                    <div class="stat-box"><span class="stat-number">60-80%</span><span>Utilization Rate</span></div>
                    <div class="stat-box"><span class="stat-number">300%+</span><span>Lifetime Equipment ROI</span></div>
                </div>
            </div>
        </div>

        <!-- RUSSIAN -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>🔄 СТРАТЕГИЯ 4: Программы Аренды Оборудования</h1>
                <p style="font-size: 1.4em;">Краткосрочная Аренда Медицинского Оборудования с Высоким Регулярным Доходом</p>
                <p style="font-size: 1.2em; margin-top: 15px;">Аренда Лицензированного DME (80-85%) + Аксессуары для Аренды (15-20%)</p>
            </div>

            <div class="section">
                <h2 class="section-title">💰 Модель Дохода</h2>
                <div class="revenue-box">
                    <h4 style="font-size: 1.8em;">Целевой Доход за 1-й Год</h4>
                    <span class="revenue-amount">$600K - $1.1M</span>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; text-align: left;">
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Аренда DME Оборудования</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$500K-$900K</p>
                            <p>80-85% от аренды BOC-лицензированного оборудования</p>
                        </div>
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Аксессуары для Аренды</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$100K-$200K</p>
                            <p>15-20% от одноразовых изделий и дополнений</p>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">Ежемесячный</span><span>Регулярный Доход</span></div>
                    <div class="stat-box"><span class="stat-number">60-75%</span><span>Валовая Маржа</span></div>
                    <div class="stat-box"><span class="stat-number">Страховка</span><span>Покрытие Medicare</span></div>
                    <div class="stat-box"><span class="stat-number">3-6 мес</span><span>Средний Срок Аренды</span></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🏥 ОСНОВНОЕ АРЕНДНОЕ ОБОРУДОВАНИЕ (80-85%)</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <h4>🛏️ Больничные Кровати (DM11)</h4>
                        <p><strong>Арендные Товары:</strong> Полуэлектрические больничные кровати, полностью электрические кровати, низкие кровати для риска падения, бариатрические кровати</p>
                        <p style="margin: 10px 0;"><strong>Месячная Аренда:</strong> $150-$400/месяц</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $120K-$250K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Арендуют:</strong> Восстановление после операции (замена бедра/колена 3-6 месяцев), хосписная помощь, временная болезнь. Большинство арендных договоров 3-6 месяцев. Страховка часто покрывает аренду.</p>
                    </div>

                    <div class="product-card">
                        <h4>♿ Инвалидные Коляски и Скутеры (M06/M07)</h4>
                        <p><strong>Арендные Товары:</strong> Ручные инвалидные коляски, электрические инвалидные коляски, мобильные скутеры, транспортные кресла</p>
                        <p style="margin: 10px 0;"><strong>Месячная Аренда:</strong> $50-$300/месяц</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $100K-$200K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Арендуют:</strong> Временные потребности в мобильности после операции, испытание перед покупкой, посетители с проблемами мобильности, доступность мероприятий/мест проведения.</p>
                    </div>

                    <div class="product-card">
                        <h4>🩺 Подъемники для Пациентов (DM21/DM22)</h4>
                        <p><strong>Арендные Товары:</strong> Подъемники Хойер (портативные напольные), потолочные подъемники, подъемники из положения сидя в положение стоя, наборы строп</p>
                        <p style="margin: 10px 0;"><strong>Месячная Аренда:</strong> $200-$500/месяц</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $80K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Арендуют:</strong> Краткосрочные перемещения пациентов, восстановление после инсульта, хосписная помощь, определение потребности перед покупкой на $3-5K.</p>
                    </div>

                    <div class="product-card">
                        <h4>💨 Кислородные Концентраторы (DM28/DM29)</h4>
                        <p><strong>Арендные Товары:</strong> Стационарные концентраторы (5-10L), портативные концентраторы, кислородные цилиндры, резервные системы</p>
                        <p style="margin: 10px 0;"><strong>Месячная Аренда:</strong> $100-$400/месяц</p>
                        <p style="color: #27ae60; font-weight: bold;">Оценка Годового Дохода: $80K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Почему Арендуют:</strong> Восстановление от пневмонии, обострения ХОБЛ, послеоперационные кислородные потребности, путешествия на большую высоту. Много временных респираторных потребностей.</p>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📦 АКСЕССУАРЫ ДЛЯ АРЕНДЫ (15-20%)</h2>
                <div class="product-card">
                    <h3 style="color: #8e44ad;">Обязательные Одноразовые Изделия и Дополнения</h3>
                    <ul class="benefits">
                        <li><strong>Аксессуары для Больничных Кроватей:</strong> Простыни/постельное белье (пациент оставляет себе), перила кровати и средства позиционирования, столики над кроватью, стойки для IV</li>
                        <li><strong>Дополнения для Инвалидных Колясок/Скутеров:</strong> Подушки (пациент покупает), подстаканники и сумки, защита от погоды, аксессуары безопасности</li>
                        <li><strong>Аксессуары для Подъемников Пациентов:</strong> Наборы строп (несколько для стирки), одноразовые вкладыши для строп, аксессуары для позиционирования</li>
                        <li><strong>Расходные Материалы для Кислорода:</strong> Канюли и трубки (одноразовые), бутылки увлажнителя, кислородосберегающие устройства</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: bold; color: #27ae60;">Оценка Годового Дохода: $100K-$200K</p>
                </div>
            </div>
        </div>

        <!-- UZBEK -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>🔄 STRATEGIYA 4: Uskuna Ijarasi Dasturlari</h1>
                <p style="font-size: 1.4em;">Yuqori Takroriy Daromad bilan Qisqa Muddatli Tibbiy Uskuna Ijarasi</p>
                <p style="font-size: 1.2em; margin-top: 15px;">Litsenziyalangan DME Ijara (80-85%) + Ijara Aksessuarlari (15-20%)</p>
            </div>

            <div class="section">
                <h2 class="section-title">💰 Daromad Modeli</h2>
                <div class="revenue-box">
                    <h4 style="font-size: 1.8em;">1-Yil Uchun Maqsadli Daromad</h4>
                    <span class="revenue-amount">$600K - $1.1M</span>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 20px; text-align: left;">
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>DME Uskuna Ijarasi</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$500K-$900K</p>
                            <p>BOC-litsenziyalangan uskuna ijarasidan 80-85%</p>
                        </div>
                        <div style="background: rgba(255,255,255,0.2); padding: 20px; border-radius: 10px;">
                            <h4>Ijara Aksessuarlari</h4>
                            <p style="font-size: 1.8em; font-weight: bold; margin: 10px 0;">$100K-$200K</p>
                            <p>Bir martalik va qo'shimchalardan 15-20%</p>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">Oylik</span><span>Takroriy Daromad</span></div>
                    <div class="stat-box"><span class="stat-number">60-75%</span><span>Yalpi Marja</span></div>
                    <div class="stat-box"><span class="stat-number">Sug'urta</span><span>Medicare Qoplami</span></div>
                    <div class="stat-box"><span class="stat-number">3-6 oy</span><span>O'rtacha Ijara Muddati</span></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🏥 ASOSIY IJARA USKUNA (80-85%)</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <h4>🛏️ Shifoxona Karavotlari (DM11)</h4>
                        <p><strong>Ijara Mahsulotlari:</strong> Yarim elektr shifoxona karavotlari, to'liq elektr karavotlar, yiqilish xavfi uchun past karavotlar, bariatrik karavotlar</p>
                        <p style="margin: 10px 0;"><strong>Oylik Ijara:</strong> $150-$400/oy</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $120K-$250K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Ijaraga Olinadi:</strong> Operatsiyadan keyingi tiklanish (kestirib/tizza almashtirish 3-6 oy), hospis parvarishi, vaqtinchalik kasallik. Ko'pchilik ijara shartnomalari 3-6 oy. Sug'urta ko'pincha ijarani qoplaydi.</p>
                    </div>

                    <div class="product-card">
                        <h4>♿ Nogironlar Aravachalari va Skuterlar (M06/M07)</h4>
                        <p><strong>Ijara Mahsulotlari:</strong> Qo'l nogironlar aravachalari, elektr nogironlar aravachalari, mobil skuterlar, transport kresilari</p>
                        <p style="margin: 10px 0;"><strong>Oylik Ijara:</strong> $50-$300/oy</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $100K-$200K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Ijaraga Olinadi:</strong> Operatsiyadan keyin vaqtinchalik harakatlanish ehtiyojlari, sotib olishdan oldin sinov, harakatlanish muammolari bo'lgan mehmonlar, tadbir/joy mavjudligi.</p>
                    </div>

                    <div class="product-card">
                        <h4>🩺 Bemorlar Ko'targichlari (DM21/DM22)</h4>
                        <p><strong>Ijara Mahsulotlari:</strong> Hoyer ko'targichlar (portativ pol), shiftga o'rnatiladigan ko'targichlar, o'tirishdan turishga ko'targichlar, osilma to'plamlari</p>
                        <p style="margin: 10px 0;"><strong>Oylik Ijara:</strong> $200-$500/oy</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $80K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Ijaraga Olinadi:</strong> Qisqa muddatli bemorlarni ko'chirish, insultdan tiklanish, hospis parvarishi, $3-5K sotib olishdan oldin ehtiyojni aniqlash.</p>
                    </div>

                    <div class="product-card">
                        <h4>💨 Kislorod Konsentratorlari (DM28/DM29)</h4>
                        <p><strong>Ijara Mahsulotlari:</strong> Statsionar konsentratorlar (5-10L), portativ konsentratorlar, kislorod tsilindrlari, zaxira tizimlari</p>
                        <p style="margin: 10px 0;"><strong>Oylik Ijara:</strong> $100-$400/oy</p>
                        <p style="color: #27ae60; font-weight: bold;">Yillik Daromad Bahosi: $80K-$180K</p>
                        <p style="font-size: 0.95em; margin-top: 10px;"><strong>Nima Uchun Ijaraga Olinadi:</strong> Pnevmoniyadan tiklanish, XOBL kuchayishlari, operatsiyadan keyingi kislorod ehtiyojlari, baland balandlikka sayohat. Ko'plab vaqtinchalik nafas olish ehtiyojlari.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(c => c.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(b => b.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            window.scrollTo(0, 0);
        }
    </script>
</body>
</html>
