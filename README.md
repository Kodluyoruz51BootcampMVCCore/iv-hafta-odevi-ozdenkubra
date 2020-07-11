## IV. Hafta Ödevleri:
- [x] [Geri dönen bilgiye göre yeşil renkte onay mesajı gösterilmesi. (örneğin:view bag)](https://www.muratoner.net/aspnet/aspnet-mvc/aspnet-mvc-viewbag-viewdata-tempdata-ile-veri-tasima)

```
public ActionResult Index()

  {

    ViewBag.Message1 = "ViewBag mesaj!";

    ViewData["Message2"] = "ViewData mesaj!";

    TempData["Message3"] = "TempData mesaj!";

   

    return View();

  }
```

```
<h2>@ViewBag.Message1</h2>

  <h2>@ViewData["Message2"]</h2>

  <h2>@TempData["Message3"]</h2>
```

- [x] AddMVC - AddMVCCore - AddDateAnnotations nedir? Nerelerde eklenmelidir?
	- [The difference between AddMvc() and AddMvcCore()](https://offering.solutions/blog/articles/2017/02/07/the-difference-between-addmvc-and-addmvccore/) 
	- [ASP.NET Core MVC 3.x – AddMvc(), AddMvcCore(), AddControllers() and other bootstrapping approaches](https://www.strathweb.com/2020/02/asp-net-core-mvc-3-x-addmvc-addmvccore-addcontrollers-and-other-bootstrapping-approaches/)
- [x] Snapshot nedir? nasıl değişir? neden alınır?
	- https://www.gencayyildiz.com/blog/asp-net-core-2-mvcde-migrations-ile-veritabani-islemleri/
	- https://docs.microsoft.com/tr-tr/aspnet/core/data/ef-mvc/migrations?view=aspnetcore-3.1
	- https://www.learnentityframeworkcore.com/migrations/model-snapshot  

- [x] Jquery Calender--> [Datapicker](https://jqueryui.com/datepicker/) --> DueAt'i takvim tipinde eklemek nasıl yapılır? Araştırınız. (DateTimeUffset tipinden atamalar oluşucak)
	- https://docs.microsoft.com/tr-tr/aspnet/mvc/overview/older-versions/using-the-html5-and-jquery-ui-datepicker-popup-calendar-with-aspnet-mvc/using-the-html5-and-jquery-ui-datepicker-popup-calendar-with-aspnet-mvc-part-4
	- http://www.kestrelblackmore.com/blog/jquery-datepicker-mvc4
- [ ] First- FirstOrDefault ve Single- SingleOrDefault nedir? Aralarındaki farkı araştırınız.

- [ ] En kısa null check nasıl yapılır?

- [ ] Partial View nedir?

- [ ] Farklı authentication bulup,aynı işleri farklı yollar ile yapanları araştırınız.

- [ ] Razor Pages/MVC Projects karşılaştırmasını yapınız.



