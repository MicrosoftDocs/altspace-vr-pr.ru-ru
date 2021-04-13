---
title: Предоставление ролей мира
description: Ознакомьтесь с системой ролей и возможностей и получите пошаговые инструкции по предоставлению пользователям ролей в Алтспацевр.
ms.date: 03/11/2021
ms.topic: article
keywords: Роли
ms.openlocfilehash: f8cd55fbd8ede6cedd199724a3e6b2413c5bc3e6
ms.sourcegitcommit: d84a6adf631ff02b106e682238f2861477caef1e
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/08/2021
ms.locfileid: "107212789"
---
# <a name="granting-world-roles"></a><span data-ttu-id="67377-104">Предоставление ролей мира</span><span class="sxs-lookup"><span data-stu-id="67377-104">Granting world roles</span></span>

<span data-ttu-id="67377-105">Алтспаце имеет систему ролей и возможностей.</span><span class="sxs-lookup"><span data-stu-id="67377-105">Altspace has a Roles and Abilities system.</span></span> <span data-ttu-id="67377-106">Каждый пользователь может иметь несколько ролей, и их роли могут отличаться в зависимости от того, где они находятся.</span><span class="sxs-lookup"><span data-stu-id="67377-106">Each person can have multiple roles and their roles can be different depending on where they are.</span></span> <span data-ttu-id="67377-107">Каждая роль, в свою очередь, предоставляет одну или несколько возможностей.</span><span class="sxs-lookup"><span data-stu-id="67377-107">Each role, in turn, gives you one or more abilities.</span></span> <span data-ttu-id="67377-108">Например, когда вы находитесь в своем собственном событии, вы автоматически получаете роли **Presenter** и **модератора** .</span><span class="sxs-lookup"><span data-stu-id="67377-108">For example, when you're in your own event, you automatically receive the **presenter** and **moderator** roles.</span></span> <span data-ttu-id="67377-109">С этими двумя ролями вы можете запускать унрули пользователей, находиться на промежуточном уровне и, возможно, выпустить конфетти.</span><span class="sxs-lookup"><span data-stu-id="67377-109">With those two roles you can kick unruly users, be on stage, and maybe release the confetti.</span></span> 

1. <span data-ttu-id="67377-110">Измените мир и прокрутите вниз до раздела **в VR** ([управление мировыми](managing-worlds.md)).</span><span class="sxs-lookup"><span data-stu-id="67377-110">Edit your World and scroll down to the **In VR** section ([How to manage Worlds](managing-worlds.md))</span></span>

![Изменение ролей в VR в разделе "мир"](images/granting-roles.png)

2. <span data-ttu-id="67377-112">Измените поле **роли** , если вы хотите предоставить определенные роли конкретным пользователям только для этого мира.</span><span class="sxs-lookup"><span data-stu-id="67377-112">Edit the **Roles** field if you want to grant specific roles to specific users just for this World.</span></span> <span data-ttu-id="67377-113">Например, если вы хотите **дать мне**  +  **модератора** и придать Кален **модератору**, добавьте следующий элемент и нажмите кнопку **сохранить**.</span><span class="sxs-lookup"><span data-stu-id="67377-113">For example, if you want to give me **presenter** + **moderator** and give Calen **moderator**, you would add the following and select **Save**.</span></span> <span data-ttu-id="67377-114">Формат: **{Role}, {username или email}** в каждой строке.</span><span class="sxs-lookup"><span data-stu-id="67377-114">The format is **{role},{username or email}** on each line.</span></span> <span data-ttu-id="67377-115">Имя пользователя не учитывает регистр.</span><span class="sxs-lookup"><span data-stu-id="67377-115">Username is case-insensitive.</span></span> 

```
presenter,jimmy
moderator,jimmy
moderator,calen
```

3. <span data-ttu-id="67377-116">Если вы снова наберете **изменить** , вы увидите в поле Roles (роли) следующее.</span><span class="sxs-lookup"><span data-stu-id="67377-116">If you select **Edit** again, you should see the following above the Roles field.</span></span> <span data-ttu-id="67377-117">Именно так вы узнаете об обновлении в базе данных.</span><span class="sxs-lookup"><span data-stu-id="67377-117">That's how you know updated in the database.</span></span>

```
Presenters: jimmy
Moderators: jimmy,calen
```

* <span data-ttu-id="67377-118">Чтобы изменения вступили в силу в Алтспаце, необходимо сбросить мир, чтобы все присоединиться к нему.</span><span class="sxs-lookup"><span data-stu-id="67377-118">In order for the change to take effect in Altspace, you should reset the world, forcing everyone to rejoin.</span></span> <span data-ttu-id="67377-119">Ниже приведен полный список ролей.</span><span class="sxs-lookup"><span data-stu-id="67377-119">There's a full list of roles below.</span></span>

4. <span data-ttu-id="67377-120">Измените поле **Контекстные роли** , если вы хотите предоставить роль каждому из них, который присоединяется к вашему миру.</span><span class="sxs-lookup"><span data-stu-id="67377-120">Edit the **Contextual Roles** field if you want to grant a role to every one that joins your World.</span></span> <span data-ttu-id="67377-121">Например, если вы хотите позволить людям работать и использовать рупор, чтобы они могли слышать друг друга, в то же время, добавьте следующее:</span><span class="sxs-lookup"><span data-stu-id="67377-121">For example, if you want to let people fly and use the megaphone so they can hear each other while far part, add the following:</span></span>

```
pilot,megaphone_only
```

<span data-ttu-id="67377-122">После выбора **обновления** сбросьте свой мир.</span><span class="sxs-lookup"><span data-stu-id="67377-122">After you select **Update**, reset the World.</span></span> <span data-ttu-id="67377-123">Это повлияет только на этот мир.</span><span class="sxs-lookup"><span data-stu-id="67377-123">This will only affect this World.</span></span> <span data-ttu-id="67377-124">Если вы хотите предоставить роли всем вселенной, измените те же поля в Вселенной.</span><span class="sxs-lookup"><span data-stu-id="67377-124">If you want to grant roles to an entire Universe, edit the same fields on the Universe.</span></span> 

## <a name="roles"></a><span data-ttu-id="67377-125">Роли</span><span class="sxs-lookup"><span data-stu-id="67377-125">Roles</span></span> 

* <span data-ttu-id="67377-126">**Выступающие** — возможности, например, могут быть на этапе</span><span class="sxs-lookup"><span data-stu-id="67377-126">**Presenter** - abilities like being able to be on stage</span></span>
* <span data-ttu-id="67377-127">**Модератор** — возможности, такие как « **Начало** », для поддержки декорум</span><span class="sxs-lookup"><span data-stu-id="67377-127">**Moderator** - abilities like **kick** to maintain decorum</span></span>
* <span data-ttu-id="67377-128">**Терраформер** — возможность использовать редактор мира</span><span class="sxs-lookup"><span data-stu-id="67377-128">**Terraformer** - ability to use the World Editor</span></span>
* <span data-ttu-id="67377-129">**Пилотный** режим — возможность переключения режима полета и порождения средства 6DOF Flight</span><span class="sxs-lookup"><span data-stu-id="67377-129">**Pilot** - ability to toggle fly mode and spawn the 6DOF flight tool</span></span>
* <span data-ttu-id="67377-130">**Megaphone_only** возможность говорить с пользователями в ушки, где бы они ни находились в мире</span><span class="sxs-lookup"><span data-stu-id="67377-130">**Megaphone_only** - ability to speak into users' ears wherever they are in the World</span></span>
* <span data-ttu-id="67377-131">**Showcase_new_sdk** — возможность создавать приложения пакета SDK для MRE</span><span class="sxs-lookup"><span data-stu-id="67377-131">**Showcase_new_sdk** - ability to spawn MRE SDK apps</span></span>

## <a name="troubleshooting"></a><span data-ttu-id="67377-132">Устранение неполадок</span><span class="sxs-lookup"><span data-stu-id="67377-132">Troubleshooting</span></span>

<span data-ttu-id="67377-133">**Можно ли удалить роли?**</span><span class="sxs-lookup"><span data-stu-id="67377-133">**Can I delete roles?**</span></span>
<span data-ttu-id="67377-134">Не из формы сейчас, так что файл a Поддержка на help.altvr.com, и мы позаботитесь об этом.</span><span class="sxs-lookup"><span data-stu-id="67377-134">Not from the form right now so file a Support request at help.altvr.com and we'll take care of it for you</span></span>

<span data-ttu-id="67377-135">**Копируются ли роли при импорте из другого мира?**</span><span class="sxs-lookup"><span data-stu-id="67377-135">**Are roles copied when a World is importing from another?**</span></span>
<span data-ttu-id="67377-136">Нет, роли не копируются</span><span class="sxs-lookup"><span data-stu-id="67377-136">No, roles aren't copied</span></span>