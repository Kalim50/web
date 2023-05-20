# web
HTML Web Design Code Snippets
<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
</head>
<body>
	<h1>عنوان صفحه</h1>
</body>
</html>
۲. این کد با استفاده از پاراگرافهای HTML، یک متن ساده ایجاد می کند:

<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
</head>
<body>
	<h1>عنوان صفحه</h1>
	<p>این یک متن ساده است.</p>
	<p>این یک متن دیگر است.</p>
</body>
</html>
۳. این کد یک لیست نامرتب در HTML ایجاد می کند:

<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
</head>
<body>
	<h1>عنوان صفحه</h1>
	<ul>
		<li>آیتم اول</li>
		<li>آیتم دوم</li>
		<li>آیتم سوم</li>
	</ul>
</body>
</html>
۴. این کد یک تصویر در HTML قرار می دهد:

<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
</head>
<body>
	<h1>عنوان صفحه</h1>
	<img src="path/to/image.jpg" alt="توضیحات تصویر">
</body>
</html>
این کدها بسیار ساده هستند و به شما در آموزش HTML برای طراحی صفحات وب کمک می کنند. با تقویت مهارت خود، می توانید از کدهای پیشرفته تری استفاده کنید و صفحات وب زیبا تری را طراحی کنید.




5/13/2023, 1:24:07 PM

کد های پیشرفته تر رو هم با توضیح هر کدوم برام بفرست . میتونی در قالب فایل متنی بفرستی ؟

5/13/2023, 1:25:27 PM

بله، البته کدهای پیشرفته‌ تر از مثال‌های قبلی پیچیده‌تر هستند و نیاز به دانش بیشتری در زمینه HTML، CSS و JavaScript دارند. در ادامه چند کد پیشرفته‌تر را برای شما آورده‌ام:

1- این کد با استفاده از تکنولوژی CSS، یک منوی Navigation Bar سفارشی در HTML ایجاد می کند:

<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
	<style>
  		.navbar {
    		background-color: #333;
    		overflow: hidden;
  		}
 		.navbar a {
    		float: left;
    		display: block;
    		color: white;
    		text-align: center;
    		padding: 14px 16px;
    		text-decoration: none;
  		}
 		.navbar a:hover {
    		background-color: #ddd;
    		color: black;
  		}
  		.active {
    		background-color: #4CAF50;
    		color: white;
  		}
	</style>
</head>
<body>
	<div class="navbar">
  		<a class="active" href="#">خانه</a>
  		<a href="#">درباره ما</a>
  		<a href="#">تماس با ما</a>
  		<a href="#">خدمات</a>
	</div>
</body>
</html>
2- این کد با استفاده از تکنولوژی CSS، یک جدول ساده در HTML ایجاد می کند:

<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
	<style>
  		table {
    		font-family: arial, sans-serif;
    		border-collapse: collapse;
    		width: 100%;
  		}
  		td, th {
    		border: 1px solid #dddddd;
    		text-align: left;
    		padding: 8px;
  		}
  		tr:nth-child(even) {
    		background-color: #dddddd;
  		}
	</style>
</head>
<body>
	<table>
  		<tr>
    		<th>نام</th>
    		<th>سن</th>
    		<th>شغل</th>
  		</tr>
  		<tr>
    		<td>علی</td>
    		<td>25</td>
    		<td>مهندس نرم افزار</td>
  		</tr>
  		<tr>
    		<td>نازنین</td>
    		<td>30</td>
    		<td>طراح وب</td>
  		</tr>
  		<tr>
    		<td>مریم</td>
    		<td>22</td>
    		<td>دانشجو</td>
  		</tr>
	</table>
</body>
</html>
3- این کد با استفاده از تکنولوژی JavaScript، یک پنجره Pop-Up را در HTML ایجاد می کند:

<!DOCTYPE html>
<html>
<head>
	<title>صفحه من</title>
	<script>
  		function openWindow() {
    		window.open("https://www.example.com", "newwindow", "width=400, height=500");
  		}
	</script>
</head>
<body>
	<button onclick="openWindow()">باز کردن پنجره جدید</button>
</body>
</html>
