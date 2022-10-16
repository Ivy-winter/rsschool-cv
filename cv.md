# **IRMA VIDGINYTE**    
email: <irmavidgin@yahoo.com>  

I am motivated to create professional websites and software. I have 15+ years of experience in finance and want to switch to IT sector.

---


## WORK EXPERIENCE
Accountant- Šiauliai State University Of Applied Sciences
08/29- now  
Accountant- AB Šiaulių bankas
10/2006- 03/2021 (10+ years of experience)  
Bank Teller- AB Šiaulių bankas
10/2000- 10/2006 (5+ years of experience)  

## EDUCATION
1. Bachelor of Science: Information Systems Technology| 2022
Šiauliai State University Of Applied Sciences, LT
2. Bachelor of Science: Business Administration|2000
Šiauliai University, LT

## LANGUAGES
- Lithuanian (native)
- Russian (Advanced)
- English (B1)

## COMPUTER SKILLS
HTML, CSS, JavaScript, Bootstrap, SQL, PHP, Excel VBA, Adobe Photoshop, Autocad, Git

Code snippet (sorting images by date (time) and view them as thumbnails):
```
<?php
$path = 'img/galerija/*.*';
$files = array();
$files = glob($path);
usort($files, function ($x, $y) {
return filemtime($x) < filemtime($y);
});
foreach ($files as $item) { ?>
    <script>
    $(document).ready(function() {
    $(".abc").append("<div class='pure-u-1 pure-u-lg-1-5 pure-u-md-1-3 pure-u-sm-1-2'><img class='mx-auto d-block' width='200px' height='200px' style='object-fit:contain;' alt='augintinis' src='<?php echo $item; ?>'/></div>");
    $(".abc div").addClass("thumbnail");
    });
 </script>
<?php
}
?>
```
## SKILL HIGHLIGHTS
- Innovative
- Critical/Analytical Thinker 
- Problem solving
- Collaborative
- Organized
- Hardworking
