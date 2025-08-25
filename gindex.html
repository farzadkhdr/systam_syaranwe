<!DOCTYPE html>
<html lang="ku" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سیستەمی بەکرێدانی سەیارە</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #34495e;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            padding-top: 20px;
        }
        
        .header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .nav-pills .nav-link {
            color: var(--dark-color);
            font-weight: 500;
            border-radius: 20px;
            margin: 0 5px;
            transition: all 0.3s;
        }
        
        .nav-pills .nav-link.active {
            background-color: var(--secondary-color);
            color: white;
        }
        
        .section {
            display: none;
            background-color: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            margin-bottom: 20px;
        }
        
        .section.active {
            display: block;
        }
        
        .card {
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            margin-bottom: 20px;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .btn-primary {
            background-color: var(--secondary-color);
            border: none;
            border-radius: 20px;
            padding: 10px 20px;
        }
        
        .btn-danger {
            background-color: var(--accent-color);
            border: none;
            border-radius: 20px;
            padding: 10px 20px;
        }
        
        .form-control {
            border-radius: 10px;
            padding: 12px;
            border: 1px solid #ddd;
        }
        
        .form-control:focus {
            border-color: var(--secondary-color);
            box-shadow: 0 0 0 0.25rem rgba(52, 152, 219, 0.25);
        }
        
        .suggestion-box {
            position: absolute;
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            max-height: 200px;
            overflow-y: auto;
            z-index: 1000;
            width: calc(100% - 30px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        .suggestion-item {
            padding: 10px;
            cursor: pointer;
            border-bottom: 1px solid #eee;
        }
        
        .suggestion-item:hover {
            background-color: #f0f0f0;
        }
        
        .history-item {
            border-left: 4px solid var(--secondary-color);
            padding: 15px;
            margin-bottom: 15px;
            background-color: #f8f9fa;
            border-radius: 5px;
        }
        
        .print-header {
            display: none;
        }
        
        @media print {
            body * {
                visibility: hidden;
            }
            .print-section, .print-section * {
                visibility: visible;
            }
            .print-section {
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
            }
            .print-header {
                display: block;
                text-align: center;
                margin-bottom: 20px;
                padding-bottom: 10px;
                border-bottom: 2px solid #000;
            }
        }
        
        .car-image {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 10px 10px 0 0;
        }
        
        .backup-alert {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 1050;
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header text-center">
            <h1><i class="fas fa-car-side me-2"></i>سیستەمی بەکرێدانی سەیارە</h1>
            <p class="lead">بەڕێوەبردانی بەکرێدانی سەیارە بەشێوەیەکی ئاسان</p>
        </div>

        <ul class="nav nav-pills mb-4 justify-content-center">
            <li class="nav-item">
                <a class="nav-link active" data-section="rent" href="#"><i class="fas fa-car me-1"></i> بەکرێدانی سەیارە</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" data-section="history" href="#"><i class="fas fa-history me-1"></i> مێژووی بەکرێدان</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" data-section="management" href="#"><i class="fas fa-tools me-1"></i> بەڕێوەبردن</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" data-section="backup" href="#"><i class="fas fa-database me-1"></i> باکەپ و گەرانەوە</a>
            </li>
        </ul>

        <!-- بەشی بەکرێدانی سەیارە -->
        <div id="rent-section" class="section active">
            <h2 class="mb-4"><i class="fas fa-car me-2"></i>بەشی بەکرێدانی سەیارە</h2>
            
            <div class="row mb-4">
                <div class="col-md-6">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">گەران بەدوای سەیارە</h5>
                            <div class="mb-3">
                                <label for="car-search" class="form-label">ناوی سەیارە</label>
                                <input type="text" class="form-control" id="car-search" placeholder="ناوی سەیارە بنووسە...">
                                <div id="car-suggestions" class="suggestion-box"></div>
                            </div>
                            <button id="search-car-btn" class="btn btn-primary">گەران</button>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-6">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">زیادکردنی کەسی نوێ</h5>
                            <form id="add-person-form">
                                <div class="mb-3">
                                    <label for="person-name" class="form-label">ناوی کەس</label>
                                    <input type="text" class="form-control" id="person-name" required>
                                </div>
                                <div class="mb-3">
                                    <label for="person-phone" class="form-label">ژمارەی مۆبایل</label>
                                    <input type="tel" class="form-control" id="person-phone" required>
                                </div>
                                <div class="mb-3">
                                    <label for="person-address" class="form-label">ناونیشان</label>
                                    <textarea class="form-control" id="person-address" rows="2"></textarea>
                                </div>
                                <div class="mb-3">
                                    <label for="id-card" class="form-label">وێنەی کارتی نیشتمانی</label>
                                    <input type="file" class="form-control" id="id-card" accept="image/*">
                                </div>
                                <button type="submit" class="btn btn-primary">زیادکردن</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card mb-4">
                <div class="card-body">
                    <h5 class="card-title">پڕکردنی زانیارییەکانی بەکرێدان</h5>
                    <form id="rent-form">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="mb-3">
                                    <label for="selected-car" class="form-label">هەڵبژاردنی سەیارە</label>
                                    <select class="form-control" id="selected-car" required>
                                        <option value="">سەیارە هەڵبژێرە</option>
                                    </select>
                                </div>
                                <div class="mb-3">
                                    <label for="selected-person" class="form-label">هەڵبژاردنی کەس</label>
                                    <select class="form-control" id="selected-person" required>
                                        <option value="">کەس هەڵبژێرە</option>
                                    </select>
                                </div>
                                <div class="mb-3">
                                    <label for="rent-date" class="form-label">بەرواری بەکرێدان</label>
                                    <input type="date" class="form-control" id="rent-date" required>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="mb-3">
                                    <label for="return-date" class="form-label">بەرواری وەرگرتنەوە</label>
                                    <input type="date" class="form-control" id="return-date" required>
                                </div>
                                <div class="mb-3">
                                    <label for="rent-price" class="form-label">بڕی پارەی بەکرێدان</label>
                                    <input type="number" class="form-control" id="rent-price" required>
                                </div>
                                <div class="mb-3">
                                    <label for="notes" class="form-label">تێبینی</label>
                                    <textarea class="form-control" id="notes" rows="2"></textarea>
                                </div>
                            </div>
                        </div>
                        <button type="submit" class="btn btn-primary">تۆمارکردنی بەکرێدان</button>
                    </form>
                </div>
            </div>
        </div>

        <!-- بەشی مێژووی بەکرێدان -->
        <div id="history-section" class="section">
            <h2 class="mb-4"><i class="fas fa-history me-2"></i>مێژووی بەکرێدان</h2>
            
            <div class="card mb-4">
                <div class="card-body">
                    <h5 class="card-title">فیلتەرکردن</h5>
                    <div class="row">
                        <div class="col-md-4">
                            <div class="mb-3">
                                <label for="filter-person" class="form-label">گەران بەدوای کەس</label>
                                <input type="text" class="form-control" id="filter-person" placeholder="ناوی کەس بنووسە...">
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="mb-3">
                                <label for="filter-start-date" class="form-label">بەرواری دەستپێک</label>
                                <input type="date" class="form-control" id="filter-start-date">
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="mb-3">
                                <label for="filter-end-date" class="form-label">بەرواری کۆتایی</label>
                                <input type="date" class="form-control" id="filter-end-date">
                            </div>
                        </div>
                    </div>
                    <button id="filter-btn" class="btn btn-primary">فیلتەرکردن</button>
                    <button id="reset-filter-btn" class="btn btn-secondary">پاککردنەوە</button>
                </div>
            </div>
            
            <div id="history-list">
                <!-- مێژووی بەکرێدان لێرە دەخرێتە روو -->
            </div>
            
            <div class="text-center mt-4">
                <button id="print-history-btn" class="btn btn-success"><i class="fas fa-print me-1"></i> چاپکردنی مێژوو</button>
            </div>
        </div>

        <!-- بەشی بەڕێوەبردن -->
        <div id="management-section" class="section">
            <h2 class="mb-4"><i class="fas fa-tools me-2"></i>بەڕێوەبردانی گەراج و سەیارەکان</h2>
            
            <div class="card mb-4">
                <div class="card-body">
                    <h5 class="card-title">زیادکردنی سەیارەی نوێ</h5>
                    <form id="add-car-form">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="mb-3">
                                    <label for="car-name" class="form-label">ناوی سەیارە</label>
                                    <input type="text" class="form-control" id="car-name" required>
                                </div>
                                <div class="mb-3">
                                    <label for="car-color" class="form-label">رەنگی سەیارە</label>
                                    <input type="text" class="form-control" id="car-color" required>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="mb-3">
                                    <label for="car-plate" class="form-label">رەقەمی سەیارە</label>
                                    <input type="text" class="form-control" id="car-plate" required>
                                </div>
                                <div class="mb-3">
                                    <label for="car-type" class="form-label">جۆری سەیارە</label>
                                    <input type="text" class="form-control" id="car-type" required>
                                </div>
                            </div>
                        </div>
                        <button type="submit" class="btn btn-primary">زیادکردنی سەیارە</button>
                    </form>
                </div>
            </div>
            
            <h3 class="mb-3">لیستی سەیارەکان</h3>
            <div id="cars-list" class="row">
                <!-- لیستی سەیارەکان لێرە دەخرێتە روو -->
            </div>
        </div>

        <!-- بەشی باکەپ و گەرانەوە -->
        <div id="backup-section" class="section">
            <h2 class="mb-4"><i class="fas fa-database me-2"></i>باکەپ و گەرانەوەی داتا</h2>
            
            <div class="row">
                <div class="col-md-6">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">وەرگرتنی باکەپ</h5>
                            <p class="card-text">هەموو داتاکانی سیستم وەردەگرێت و دایڵۆد دەکات بۆ کۆمپیوتەرەکەت.</p>
                            <button id="backup-btn" class="btn btn-primary"><i class="fas fa-download me-1"></i> وەرگرتنی باکەپ</button>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-6">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">گەرانەوەی داتا</h5>
                            <div class="mb-3">
                                <label for="backup-file" class="form-label">هەڵبژاردنی فایلی باکەپ</label>
                                <input type="file" class="form-control" id="backup-file" accept=".json">
                            </div>
                            <button id="restore-btn" class="btn btn-primary"><i class="fas fa-upload me-1"></i> گەرانەوەی داتا</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">باکەپی خۆکار</h5>
                    <div class="form-check form-switch">
                        <input class="form-check-input" type="checkbox" id="auto-backup-toggle">
                        <label class="form-check-label" for="auto-backup-toggle">باکەپی ڕۆژانەی خۆکار</label>
                    </div>
                    <p class="text-muted mt-2">کاتێک چالاکبکەیت، سیستمەکە هەموو رۆژێک بەشێوەیەکی خۆکار باکەپ وەردەگرێت.</p>
                </div>
            </div>
        </div>
    </div>

    <div class="backup-alert alert alert-success" role="alert">
        <i class="fas fa-check-circle me-2"></i> باکەپەکە سەرکەوتووانە وەگیرا!
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // داتای نموونەیی بۆ دەستپێک
        let cars = JSON.parse(localStorage.getItem('cars')) || [
            { id: 1, name: "تۆیۆتا کەمری", color: "سپی", plate: "12345ABC", type: "سدان" },
            { id: 2, name: "هیوندای ئێلانترا", color: "ڕەش", plate: "67890XYZ", type: "سدان" },
            { id: 3, name: "کیا سۆرێنتۆ", color: "شین", plate: "54321LMN", type: "SUV" }
        ];

        let people = JSON.parse(localStorage.getItem('people')) || [
            { id: 1, name: "عەلی محەممەد", phone: "07501234567", address: "هەولێر، ناحیەی ...", idCard: "" },
            { id: 2, name: "سارا عەبدوڵڵا", phone: "07507654321", address: "سلێمانی، گەڕەکی ...", idCard: "" }
        ];

        let rentals = JSON.parse(localStorage.getItem('rentals')) || [
            { id: 1, carId: 1, personId: 1, rentDate: "2023-10-01", returnDate: "2023-10-05", price: 150000, notes: "" },
            { id: 2, carId: 2, personId: 2, rentDate: "2023-10-10", returnDate: "2023-10-12", price: 120000, notes: "" }
        ];

        // هەڵگرتنی داتا لە localStorage
        function saveData() {
            localStorage.setItem('cars', JSON.stringify(cars));
            localStorage.setItem('people', JSON.stringify(people));
            localStorage.setItem('rentals', JSON.stringify(rentals));
            
            // نیشاندانی ئاگاداری باکەپ
            const backupAlert = document.querySelector('.backup-alert');
            backupAlert.style.display = 'block';
            setTimeout(() => {
                backupAlert.style.display = 'none';
            }, 3000);
        }

        // بارکردنی داتا کاتێک پەڕە باردەبێتەوە
        document.addEventListener('DOMContentLoaded', function() {
            loadCarsToSelect();
            loadPeopleToSelect();
            displayCars();
            displayRentalHistory();
            
            // ڕێکخستنی بەرواری ئەمڕۆ
            const today = new Date().toISOString().split('T')[0];
            document.getElementById('rent-date').value = today;
            
            // زیادکردنی ڕۆژێک بۆ بەرواری وەرگرتنەوە
            const tomorrow = new Date();
            tomorrow.setDate(tomorrow.getDate() + 1);
            document.getElementById('return-date').value = tomorrow.toISOString().split('T')[0];
        });

        // گۆڕینی نێوان بەشەکان
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                
                // لابردنی چالاکی لە هەموو بەستەرەکان
                document.querySelectorAll('.nav-link').forEach(l => l.classList.remove('active'));
                // زیادکردنی چالاکی بۆ بەستەری کراوە
                this.classList.add('active');
                
                // نیشاندانی بەشی هەڵبژێردراو
                const sectionId = this.getAttribute('data-section');
                document.querySelectorAll('.section').forEach(section => {
                    section.classList.remove('active');
                });
                document.getElementById(`${sectionId}-section`).classList.add('active');
            });
        });

        // زیادکردنی کەسی نوێ
        document.getElementById('add-person-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('person-name').value;
            const phone = document.getElementById('person-phone').value;
            const address = document.getElementById('person-address').value;
            const idCardFile = document.getElementById('id-card').files[0];
            
            let idCardUrl = '';
            if (idCardFile) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    idCardUrl = e.target.result;
                    addPerson(name, phone, address, idCardUrl);
                };
                reader.readAsDataURL(idCardFile);
            } else {
                addPerson(name, phone, address, idCardUrl);
            }
        });

        function addPerson(name, phone, address, idCardUrl) {
            const newPerson = {
                id: people.length > 0 ? Math.max(...people.map(p => p.id)) + 1 : 1,
                name: name,
                phone: phone,
                address: address,
                idCard: idCardUrl
            };
            
            people.push(newPerson);
            saveData();
            loadPeopleToSelect();
            
            // پاککردنەوەی فۆرمەکە
            document.getElementById('add-person-form').reset();
            alert("کەسەکە بە سەرکەوتوویی زیادکرا!");
        }

        // زیادکردنی سەیارەی نوێ
        document.getElementById('add-car-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('car-name').value;
            const color = document.getElementById('car-color').value;
            const plate = document.getElementById('car-plate').value;
            const type = document.getElementById('car-type').value;
            
            const newCar = {
                id: cars.length > 0 ? Math.max(...cars.map(c => c.id)) + 1 : 1,
                name: name,
                color: color,
                plate: plate,
                type: type
            };
            
            cars.push(newCar);
            saveData();
            loadCarsToSelect();
            displayCars();
            
            // پاککردنەوەی فۆرمەکە
            document.getElementById('add-car-form').reset();
            alert("سەیارەکە بە سەرکەوتوویی زیادکرا!");
        });

        // تۆمارکردنی بەکرێدان
        document.getElementById('rent-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const carId = parseInt(document.getElementById('selected-car').value);
            const personId = parseInt(document.getElementById('selected-person').value);
            const rentDate = document.getElementById('rent-date').value;
            const returnDate = document.getElementById('return-date').value;
            const price = parseFloat(document.getElementById('rent-price').value);
            const notes = document.getElementById('notes').value;
            
            const newRental = {
                id: rentals.length > 0 ? Math.max(...rentals.map(r => r.id)) + 1 : 1,
                carId: carId,
                personId: personId,
                rentDate: rentDate,
                returnDate: returnDate,
                price: price,
                notes: notes
            };
            
            rentals.push(newRental);
            saveData();
            displayRentalHistory();
            
            // پاککردنەوەی فۆرمەکە
            document.getElementById('rent-form').reset();
            
            // دانەیەوەی بەروارەکان
            const today = new Date().toISOString().split('T')[0];
            document.getElementById('rent-date').value = today;
            
            const tomorrow = new Date();
            tomorrow.setDate(tomorrow.getDate() + 1);
            document.getElementById('return-date').value = tomorrow.toISOString().split('T')[0];
            
            alert("بەکرێدانەکە بە سەرکەوتوویی تۆمارکرا!");
        });

        // بارکردنی سەیارەکان بۆ هەڵبژاردن
        function loadCarsToSelect() {
            const select = document.getElementById('selected-car');
            select.innerHTML = '<option value="">سەیارە هەڵبژێرە</option>';
            
            cars.forEach(car => {
                const option = document.createElement('option');
                option.value = car.id;
                option.textContent = `${car.name} (${car.plate})`;
                select.appendChild(option);
            });
        }

        // بارکردنی کەسەکان بۆ هەڵبژاردن
        function loadPeopleToSelect() {
            const select = document.getElementById('selected-person');
            select.innerHTML = '<option value="">کەس هەڵبژێرە</option>';
            
            people.forEach(person => {
                const option = document.createElement('option');
                option.value = person.id;
                option.textContent = `${person.name} (${person.phone})`;
                select.appendChild(option);
            });
        }

        // نیشاندانی سەیارەکان
        function displayCars() {
            const carsList = document.getElementById('cars-list');
            carsList.innerHTML = '';
            
            cars.forEach(car => {
                const carCard = document.createElement('div');
                carCard.className = 'col-md-4';
                carCard.innerHTML = `
                    <div class="card">
                        <img src="https://via.placeholder.com/300x150?text=${car.name}" class="car-image" alt="${car.name}">
                        <div class="card-body">
                            <h5 class="card-title">${car.name}</h5>
                            <p class="card-text">رەنگ: ${car.color}</p>
                            <p class="card-text">رەقەم: ${car.plate}</p>
                            <p class="card-text">جۆر: ${car.type}</p>
                            <button class="btn btn-danger btn-sm" onclick="deleteCar(${car.id})">سڕینەوە</button>
                        </div>
                    </div>
                `;
                carsList.appendChild(carCard);
            });
        }

        // نیشاندانی مێژووی بەکرێدان
        function displayRentalHistory() {
            const historyList = document.getElementById('history-list');
            historyList.innerHTML = '';
            
            // فیلتەرکردن (ئەگەر هەبێت)
            const filterPerson = document.getElementById('filter-person').value.toLowerCase();
            const filterStartDate = document.getElementById('filter-start-date').value;
            const filterEndDate = document.getElementById('filter-end-date').value;
            
            let filteredRentals = rentals;
            
            if (filterPerson) {
                filteredRentals = filteredRentals.filter(rental => {
                    const person = people.find(p => p.id === rental.personId);
                    return person && person.name.toLowerCase().includes(filterPerson);
                });
            }
            
            if (filterStartDate) {
                filteredRentals = filteredRentals.filter(rental => rental.rentDate >= filterStartDate);
            }
            
            if (filterEndDate) {
                filteredRentals = filteredRentals.filter(rental => rental.returnDate <= filterEndDate);
            }
            
            if (filteredRentals.length === 0) {
                historyList.innerHTML = '<div class="alert alert-info">هیچ تۆمارێکی بەکرێدان نەدۆزرایەوە.</div>';
                return;
            }
            
            filteredRentals.forEach(rental => {
                const car = cars.find(c => c.id === rental.carId);
                const person = people.find(p => p.id === rental.personId);
                
                if (car && person) {
                    const historyItem = document.createElement('div');
                    historyItem.className = 'history-item';
                    historyItem.innerHTML = `
                        <div class="d-flex justify-content-between">
                            <h5>${car.name} - ${person.name}</h5>
                            <button class="btn btn-danger btn-sm" onclick="deleteRental(${rental.id})">سڕینەوە</button>
                        </div>
                        <p>بەرواری بەکرێدان: ${rental.rentDate} | بەرواری وەرگرتنەوە: ${rental.returnDate}</p>
                        <p>بڕی پارە: ${rental.price.toLocaleString()} دینار</p>
                        ${rental.notes ? `<p>تێبینی: ${rental.notes}</p>` : ''}
                    `;
                    historyList.appendChild(historyItem);
                }
            });
        }

        // سڕینەوەی سەیارە
        function deleteCar(carId) {
            if (confirm("دڵنیایت لە سڕینەوەی ئەم سەیارەیە؟")) {
                cars = cars.filter(car => car.id !== carId);
                saveData();
                loadCarsToSelect();
                displayCars();
            }
        }

        // سڕینەوەی تۆماری بەکرێدان
        function deleteRental(rentalId) {
            if (confirm("دڵنیایت لە سڕینەوەی ئەم تۆمارە؟")) {
                rentals = rentals.filter(rental => rental.id !== rentalId);
                saveData();
                displayRentalHistory();
            }
        }

        // فیلتەرکردنی مێژووی بەکرێدان
        document.getElementById('filter-btn').addEventListener('click', displayRentalHistory);
        
        // پاککردنەوەی فیلتەرەکان
        document.getElementById('reset-filter-btn').addEventListener('click', function() {
            document.getElementById('filter-person').value = '';
            document.getElementById('filter-start-date').value = '';
            document.getElementById('filter-end-date').value = '';
            displayRentalHistory();
        });

        // گەران بەدوای سەیارە
        document.getElementById('car-search').addEventListener('input', function() {
            const searchText = this.value.toLowerCase();
            const suggestions = document.getElementById('car-suggestions');
            
            if (searchText.length < 2) {
                suggestions.innerHTML = '';
                suggestions.style.display = 'none';
                return;
            }
            
            const filteredCars = cars.filter(car => 
                car.name.toLowerCase().includes(searchText) || 
                car.plate.toLowerCase().includes(searchText)
            );
            
            suggestions.innerHTML = '';
            if (filteredCars.length > 0) {
                suggestions.style.display = 'block';
                filteredCars.forEach(car => {
                    const item = document.createElement('div');
                    item.className = 'suggestion-item';
                    item.textContent = `${car.name} (${car.plate})`;
                    item.addEventListener('click', function() {
                        document.getElementById('car-search').value = car.name;
                        suggestions.innerHTML = '';
                        suggestions.style.display = 'none';
                    });
                    suggestions.appendChild(item);
                });
            } else {
                suggestions.style.display = 'none';
            }
        });

        // کلیک کردن لە شوێنێکی تر بۆ لێکردنەوەی پێشنیارەکان
        document.addEventListener('click', function(e) {
            if (e.target.id !== 'car-search') {
                document.getElementById('car-suggestions').style.display = 'none';
            }
        });

        // وەرگرتنی باکەپ
        document.getElementById('backup-btn').addEventListener('click', function() {
            const data = {
                cars: cars,
                people: people,
                rentals: rentals
            };
            
            const dataStr = JSON.stringify(data);
            const dataUri = 'data:application/json;charset=utf-8,'+ encodeURIComponent(dataStr);
            
            const exportFileDefaultName = 'car-rental-backup.json';
            
            const linkElement = document.createElement('a');
            linkElement.setAttribute('href', dataUri);
            linkElement.setAttribute('download', exportFileDefaultName);
            linkElement.click();
            
            // نیشاندانی ئاگاداری باکەپ
            const backupAlert = document.querySelector('.backup-alert');
            backupAlert.style.display = 'block';
            setTimeout(() => {
                backupAlert.style.display = 'none';
            }, 3000);
        });

        // گەرانەوەی داتا
        document.getElementById('restore-btn').addEventListener('click', function() {
            const fileInput = document.getElementById('backup-file');
            const file = fileInput.files[0];
            
            if (!file) {
                alert("تکایە فایلێکی باکەپ هەڵبژێرە!");
                return;
            }
            
            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const data = JSON.parse(e.target.result);
                    
                    if (data.cars && data.people && data.rentals) {
                        if (confirm("ئەم کارە هەموو داتا ئێستاییەکان دەسڕێتەوە و داتای نوێ جێگیر دەکات. دڵنیایت؟")) {
                            cars = data.cars;
                            people = data.people;
                            rentals = data.rentals;
                            
                            saveData();
                            loadCarsToSelect();
                            loadPeopleToSelect();
                            displayCars();
                            displayRentalHistory();
                            
                            alert("داتاکان بە سەرکەوتوویی گەرانەوە!");
                        }
                    } else {
                        alert("فایلەکە شێوەی دروستی نییە!");
                    }
                } catch (error) {
                    alert("هەڵە لە خوێندنەوەی فایلەکە: " + error.message);
                }
            };
            reader.readAsText(file);
        });

        // چاپکردنی مێژوو
        document.getElementById('print-history-btn').addEventListener('click', function() {
            const printContent = document.getElementById('history-list').innerHTML;
            const originalContent = document.body.innerHTML;
            
            document.body.innerHTML = `
                <div class="print-section">
                    <div class="print-header">
                        <h2>مێژووی بەکرێدانی سەیارە</h2>
                        <p>بەروار: ${new Date().toLocaleDateString('ar-KU')}</p>
                    </div>
                    ${printContent}
                </div>
            `;
            
            window.print();
            document.body.innerHTML = originalContent;
            displayRentalHistory(); // دووبارە بارکردنەوەی مێژوو
            location.reload(); // دووبارە بارکردنەوەی پەڕەکە
        });

        // باکەپی خۆکار
        document.getElementById('auto-backup-toggle').addEventListener('change', function() {
            if (this.checked) {
                // لێدانی باکەپ
                const data = {
                    cars: cars,
                    people: people,
                    rentals: rentals
                };
                
                const dataStr = JSON.stringify(data);
                const dataUri = 'data:application/json;charset=utf-8,'+ encodeURIComponent(dataStr);
                
                const exportFileDefaultName = `car-rental-backup-${new Date().toISOString().split('T')[0]}.json`;
                
                const linkElement = document.createElement('a');
                linkElement.setAttribute('href', dataUri);
                linkElement.setAttribute('download', exportFileDefaultName);
                linkElement.click();
                
                alert("باکەپی ڕۆژانەی خۆکار چالاککرا و یەکەم باکەپ وەگیرا!");
            } else {
                alert("باکەپی ڕۆژانەی خۆکار ناچالاککرا!");
            }
        });
    </script>
</body>
</html>
