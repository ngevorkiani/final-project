# Marketing Agency Website

ეს არის საბოლოო პროექტი, რომელიც წარმოადგენს მარკეტინგული სააგენტოს მრავალგვერდიან, სრულად რესპონსიულ ვებ-გვერდს.

## გამოყენებული ტექნოლოგიები

- HTML5
- SCSS (Sass)
- Bootstrap 5
- Media Queries (რესპონსიული დიზაინი)
- Git / GitHub

## გვერდები

- **Home** — მთავარი გვერდი hero-სექციით (Bootstrap Carousel), სერვისების მიმოხილვით, გუნდით, testimonial-ებით და ბლოგის პრევიუთი
- **About Us** — კომპანიის შესახებ ინფორმაცია
- **Services** — სერვისების დეტალური აღწერა
- **Contact Us** — საკონტაქტო ინფორმაცია, ფორმა და Google Maps რუკა
- **Team** — გუნდის წევრები
- **Faq** — ხშირად დასმული კითხვები (HTML `<details>` ელემენტით, JS-ის გარეშე)
- **Pricing Plan** — ფასების გეგმები

## სტრუქტურა

final-project/
├── index.html
├── about.html
├── services.html
├── contact.html
├── team.html
├── faq.html
├── pricing.html
├── css/
│ └── main.css
├── scss/
│ ├── main.scss
│ ├── \_variables.scss
│ ├── \_mixins.scss
│ ├── \_global.scss
│ ├── \_header.scss
│ ├── \_home.scss
│ ├── \_about.scss
│ ├── \_services.scss
│ ├── \_contact.scss
│ └── \_responsive.scss
└── README.md

## როგორ გავუშვათ ლოკალურად

1. Clone გააკეთე ან ჩამოტვირთე repository
2. გახსენი `index.html` ბრაუზერში (რეკომენდირებულია VS Code-ის Live Server გაფართოებით)

## SCSS-ის კომპილირება

SCSS ფაილების რედაქტირების შემდეგ საჭიროა კომპილირება CSS-ად. ეს გაკეთებულია VS Code-ის **Live Sass Compiler** გაფართოებით.
