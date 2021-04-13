---
title: Импорт моделей Глтф
description: Узнайте, как правильно импортировать трехмерные модели Глтф в возможности Алтспацевр и устранять любые проблемы.
ms.date: 03/11/2021
ms.topic: article
keywords: модели, Глтф, импорт, скетчфаб, устранение неполадок
ms.openlocfilehash: 4489f90832bd1cf85ff161caed11684257cce6ab
ms.sourcegitcommit: d84a6adf631ff02b106e682238f2861477caef1e
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/08/2021
ms.locfileid: "107213256"
---
# <a name="importing-gltf-models"></a><span data-ttu-id="b835a-104">Импорт моделей Глтф</span><span class="sxs-lookup"><span data-stu-id="b835a-104">Importing glTF models</span></span>

> [!NOTE]
> <span data-ttu-id="b835a-105">Эта функция доступна для выбора пользователей в программе раннего доступа в данный момент.</span><span class="sxs-lookup"><span data-stu-id="b835a-105">This feature is available for select users in the Early Access program at this time.</span></span>

<span data-ttu-id="b835a-106">Одним из способов переноса трехмерных моделей и сцен в Алтспаце является использование [стандарта глтф](https://en.wikipedia.org/wiki/GlTF).</span><span class="sxs-lookup"><span data-stu-id="b835a-106">One way to bring 3D models and scenes into Altspace is using the [glTF standard](https://en.wikipedia.org/wiki/GlTF).</span></span> <span data-ttu-id="b835a-107">Можно передать GLBA-файл (упакованный Глтф), чтобы создать модель, которую позже можно будет порождать в редакторе мира.</span><span class="sxs-lookup"><span data-stu-id="b835a-107">You can upload a .glb file (packed glTF) to create a Model that you can later spawn in the World Editor.</span></span> <span data-ttu-id="b835a-108">Это альтернатива [отправке собственных наборов](uploading-custom-kits.md).</span><span class="sxs-lookup"><span data-stu-id="b835a-108">It's an alternative to [uploading your own Kits](uploading-custom-kits.md).</span></span> <span data-ttu-id="b835a-109">Мы рекомендуем создавать модели для быстрых демонстраций, так как вам не нужно использовать Unity и пакеты, если требуется максимально повысить производительность и повторное использование.</span><span class="sxs-lookup"><span data-stu-id="b835a-109">We recommend creating Models for quick demonstrations because you won't need to use Unity, and Kits when you want to maximize performance and reusability.</span></span> 

1. <span data-ttu-id="b835a-110">Поиск некоторых Глтф трехмерных ресурсов.</span><span class="sxs-lookup"><span data-stu-id="b835a-110">Find some glTF 3D assets.</span></span> <span data-ttu-id="b835a-111">Одно из расположений для поиска — Скетчфаб (попробуйте применить фильтрацию для **загружаемых** моделей, [например).](https://sketchfab.com/search?features=downloadable&q=low+poly+wolf&sort_by=-pertinence&type=models)</span><span class="sxs-lookup"><span data-stu-id="b835a-111">One place to search is Sketchfab (try filtering for **Downloadable** models like [this](https://sketchfab.com/search?features=downloadable&q=low+poly+wolf&sort_by=-pertinence&type=models)).</span></span> <span data-ttu-id="b835a-112">Найдя его, выберите **скачать трехмерную модель**:</span><span class="sxs-lookup"><span data-stu-id="b835a-112">Once you find it, select **Download 3D Model**:</span></span>

![модель трехмерной Dog из Скетчфаб](images/importing-models-img-01.png)

2. <span data-ttu-id="b835a-114">Скопируйте ссылку на модель и прочтите требования к лицензированию.</span><span class="sxs-lookup"><span data-stu-id="b835a-114">Copy the link to the model and read the licensing requirements.</span></span> 
3. <span data-ttu-id="b835a-115">Скачать версию с **автопреобразованным форматом (глтф)**</span><span class="sxs-lookup"><span data-stu-id="b835a-115">Download the **Autoconverted Format (glTF)** version</span></span>

![Параметры загрузки скетчфаб с выделенным автопреобразованным форматом](images/importing-models-img-02.png)

4. <span data-ttu-id="b835a-117">Откройте сайт [пакета GLBA](https://glb-packer.glitch.me) и установите флажок **преобразовать PNG в формат JPEG (бета-версия)** .</span><span class="sxs-lookup"><span data-stu-id="b835a-117">Open the [GLB Packer](https://glb-packer.glitch.me) site and check the box **Convert PNG to JPEG (beta)**</span></span>
5. <span data-ttu-id="b835a-118">Распакуйте Скачанные файлы Глтф и перетащите их на вкладку браузера пакета GLBA Pack.</span><span class="sxs-lookup"><span data-stu-id="b835a-118">Uncompress the glTF files you downloaded and drag them all at once into the GLB Packer browser tab</span></span>

![Окно, показывающее распаковку модели](images/importing-models-img-03.png)

6. <span data-ttu-id="b835a-120">В зависимости от числа и размера файлов обработка может занять некоторое время.</span><span class="sxs-lookup"><span data-stu-id="b835a-120">Depending on the number and size of the files, it may take a while to process.</span></span> <span data-ttu-id="b835a-121">По завершении обработки будет скачан файл **out. GLBA** .</span><span class="sxs-lookup"><span data-stu-id="b835a-121">When processing is done, an **out.glb** file will be downloaded.</span></span> <span data-ttu-id="b835a-122">Переименуйте этот файл в что-нибудь информативное — это имя объекта в мире (например, **Low поли Wolf. GLBA).**</span><span class="sxs-lookup"><span data-stu-id="b835a-122">Rename that file to something informative--this will be the name of the object in the world (e.g **Low Poly Wolf.glb**)</span></span>
7. <span data-ttu-id="b835a-123">Перейдите к [altvr.com > другие > модели](https://account.altvr.com/users/sign_in) и выберите **создать** .</span><span class="sxs-lookup"><span data-stu-id="b835a-123">Navigate to [altvr.com > More > Models](https://account.altvr.com/users/sign_in) and select **Create**</span></span>
8. <span data-ttu-id="b835a-124">Укажите расположение файла GLBA и убедитесь, что вы скопировали ссылку Скетчфаб в описание для атрибутов.</span><span class="sxs-lookup"><span data-stu-id="b835a-124">Specify the location of the .glb file and make sure you copy the Sketchfab link into the description for attribution.</span></span> <span data-ttu-id="b835a-125">При необходимости можно указать изображение для предварительного просмотра, а затем выбрать **создать модель**:</span><span class="sxs-lookup"><span data-stu-id="b835a-125">You can specify a preview image if you want, then select **Create Model**:</span></span>

![Предварительный просмотр модели в Алтспацевр](images/importing-models-img-04.png)

9. <span data-ttu-id="b835a-127">Выберите **Копировать в буфер обмена**</span><span class="sxs-lookup"><span data-stu-id="b835a-127">Select **Copy to Clipboard**</span></span>
10. <span data-ttu-id="b835a-128">Откройте **Редактор мира > основы алтспаце > > глтф**</span><span class="sxs-lookup"><span data-stu-id="b835a-128">Open the **World Editor > Altspace > Basics > GLTF**</span></span>
11. <span data-ttu-id="b835a-129">Вставьте URL-адрес и нажмите кнопку **подтвердить** .</span><span class="sxs-lookup"><span data-stu-id="b835a-129">Paste in your url and select **Confirm**</span></span>

<span data-ttu-id="b835a-130">Поздравляем!</span><span class="sxs-lookup"><span data-stu-id="b835a-130">Congrats!</span></span> <span data-ttu-id="b835a-131">Вы только что породили первую модель.</span><span class="sxs-lookup"><span data-stu-id="b835a-131">You just spawned your first Model.</span></span>

## <a name="troubleshooting"></a><span data-ttu-id="b835a-132">Устранение неполадок</span><span class="sxs-lookup"><span data-stu-id="b835a-132">Troubleshooting</span></span>

<span data-ttu-id="b835a-133">**При нажатии кнопки **подтвердить** ничего не произошло**</span><span class="sxs-lookup"><span data-stu-id="b835a-133">**When I clicked **Confirm** nothing happened**</span></span>
    * <span data-ttu-id="b835a-134">Сейчас у нас есть ограничение в 100 тысячах многоугольников.</span><span class="sxs-lookup"><span data-stu-id="b835a-134">We currently have a 100k polygon limit.</span></span> <span data-ttu-id="b835a-135">В случае сбоя удалите объект, чтобы избежать потенциальных проблем с пользователями, присоединенными к вашему миру.</span><span class="sxs-lookup"><span data-stu-id="b835a-135">If it fails, delete the Object to avoid potential problems with users joining your World</span></span>
    * <span data-ttu-id="b835a-136">Могут возникнуть другие проблемы с ресурсом.</span><span class="sxs-lookup"><span data-stu-id="b835a-136">There may be other problems with the asset.</span></span> <span data-ttu-id="b835a-137">Попробуйте использовать ресурсы с минимальными возможными многоугольниками.</span><span class="sxs-lookup"><span data-stu-id="b835a-137">Try to use assets with as few polygons as possible.</span></span>
    * <span data-ttu-id="b835a-138">Модель, в которой Вы находитесь, может быть небольшой или большой.</span><span class="sxs-lookup"><span data-stu-id="b835a-138">The model you're bringing in may be small or large.</span></span> <span data-ttu-id="b835a-139">Попробуйте увеличить или уменьшить масштаб или переместить аватар. возможно, вы заходите в модель.</span><span class="sxs-lookup"><span data-stu-id="b835a-139">Try increasing/decreasing the Scale or move your avatar around, you might be standing inside the model!</span></span>

<span data-ttu-id="b835a-140">**Загрузка происходит слишком долго** Скорость подключения для других пользователей в мире будет зависеть от скорости соединения.</span><span class="sxs-lookup"><span data-stu-id="b835a-140">**It's slow to load** How quickly other users in the World load it will depend on their connection speeds.</span></span> <span data-ttu-id="b835a-141">Кроме того, он не кэшируется как активы комплекта.</span><span class="sxs-lookup"><span data-stu-id="b835a-141">It's also not cached like Kit assets.</span></span> <span data-ttu-id="b835a-142">Если разместить его в вашей домашней папке, вы будете перезагружать ту же модель при каждом соединении, что не замечательно.</span><span class="sxs-lookup"><span data-stu-id="b835a-142">If you place one in your Home, you'll end up redownloading the same Model every time you join, which isn't great.</span></span>

<span data-ttu-id="b835a-143">**Нет конфликтов** По умолчанию для объектов, которые были перенесены таким образом, нет конфликтов</span><span class="sxs-lookup"><span data-stu-id="b835a-143">**There's no collision** By default there's no collision on the objects that are brought in this way</span></span>

<span data-ttu-id="b835a-144">**При его порождении элементы управления теряются на шести дофах или в этом случае, так что трудно управлять им** Да, мы осведомлены об этих проблемах и надеемся устранить их в ближайшее время.</span><span class="sxs-lookup"><span data-stu-id="b835a-144">**When I spawn it, I lose my controls on six DOF or I'm inside so it's hard to manipulate it** Yes, we're aware of these issues and hope to address them soon.</span></span>  