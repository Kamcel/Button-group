# Button-group
How to add dropdowns to buttons


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page title</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
</head>
<body>
    <div class="btn-group-vertical mx-5 my-5 p-2">
        <div class="btn-group">
            <button class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Apple</button>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">iPhone X</a>
                    <a class="dropdown-item" href="#">iPhone 11</a>
                    <a class="dropdown-item" href="#">iPhone 12</a>
                </div>
        </div>
        
        <div class="btn-group">
            <button class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">Samsung</button>
            <div class="dropdown-menu">
                <a class="dropdown-item" href="#">Samsung A10</a>
                <a class="dropdown-item" href="#">Samsung S10</a>
                <a class="dropdown-item" href="#">Samsung Z10</a>
            </div>
        </div>
        
        <div class="btn-group">
            <button class="btn btn-dark dropdown-toggle" data-bs-toggle="dropdown">Nokia</button>
            <div class="dropdown-menu">
                <a class="dropdown-item" href="#">Nokia Lumia</a>
                <a class="dropdown-item" href="#">Nokia Zumia</a>
                <a class="dropdown-item" href="#"> Nokia Bumia</a>
            </div>
        </div>
        
        <div class="btn-group">
            <button class="btn btn-danger dropdown-toggle" data-bs-toggle="dropdown">Oppo</button>
            <div class="dropdown-menu bg-danger">
                <a class="dropdown-item" href="#">Oppo Reno 1</a>
                <a class="dropdown-item" href="#">Oppo Reno 2</a>
                <a  class="dropdown-item" href="#">Oppo Reno 3</a>
            </div>
        </div>
    </div>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
</body>

