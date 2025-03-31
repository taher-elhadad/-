<!DOCTYPE html>
<html lang="ar">
<head>
    <title>فتح الكاميرا عبر اختيار ملف</title>
</head>
<body>
    <input type="file" accept="image/*" capture="environment" id="cameraInput">
    <script>
        document.getElementById("cameraInput").click();
    </script>
</body>
</html>
