В статье [1] авторы Yonghong Tiana, Bing Zhenga, Yanfang Wanga, Yue Zhanga, Qi Wua рассматривают персонализированную рекомендательную систему для библиотек высших учебных заведений на основе гибридного алгоритма рекомендации. 
Для генерации рекомендаций использовался как методы коллаборативной фильтрации (Collaborative Filtering, CF) так и методы фильтрации на основе контента (Content-Based Filtering, CBF), которые позже были объединены в гибридный алгоритм (Hybrid Recommendation Algorithm, HRA).
В фильтрации на основе контента алгоритм анализирует свойства объекта, например, автора, издательство, ключевые слова и тему, и генерирует рекомендации на основе сходства свойств. В коллаборативной фильтрации алгоритм использует данные о предпочтениях других пользователей, чтобы определить рекомендации для данного пользователя.
Для более точной рекомендации был использован гибридный подход, который объединяет результаты обоих методов. Этот подход повысил точность рекомендаций, поскольку он учитывает не только личные предпочтения пользователя, но и характеристики объектов, которые он рассматривает.
В эксперименте, авторы использовали данные библиотеки Inner Mongolia University of Technology за период с 2014 по 2016 год, которые включали в себя информацию 43 153 пользователей, 70 000 книг и 200 593 записей о книгах, взятых в аренду пользователями. Для решения проблемы разреженности, авторы использовали три метода. Метод 1 заменял книгу на классификацию книг и использовал матрицу пользователя-категории вместо матрицы пользователя-книги. Метод 2 выбирал 30 общих категорий в качестве собственного вектора пользователя. Метод 3 использовал кластеризацию, где количество кластеров было установлено на k = 15, а максимальное количество итераций - 50. Результаты кластеризации представлены в таблице 1, где указано количество пользователей в каждом кластере. Результаты исслодования показали, что метод 3 был наиболее эффективным, позволив существенно снизить разреженность до 76.42%, в то время как разреженность матрицы пользователя-книги составила 99.99%, а метод 1 смог сократить ее только до 98.7%.


"College Library Personalized Recommendation System Based on Hybrid Recommendation Algorithm"




В статье [2] авторы провели обзор методов и технологий, используемых для создания персонализированных рекомендаций в сфере недвижимости, включая продажу и аренду. Авторы статьи - Alireza Gharahighehi, Konstantinos Pliakos and Celine Vens.

Авторы рассмотрели различные алгоритмы и подходы, используемые для создания персонализированных рекомендаций в сфере недвижимости, включая коллаборативную фильтрацию и методы фильтрации на основе контента. Они также рассмотрели различные факторы, учитываемые при создании персонализированных рекомендаций, такие как история поиска клиента, его предпочтения, демографические данные и местоположение.

Исследовательская часть статьи включала описание эксперимента, проведенного авторами, чтобы оценить эффективность различных методов создания персонализированных рекомендаций в сфере недвижимости. Авторы использовали данные реальных пользователей недвижимости, собранные из различных источников, и сравнили различные алгоритмы и подходы по метрикам точности и полезности рекомендаций.

В результате исследования авторы пришли к выводу, что использование гибридных методов, объединяющих коллаборативную фильтрацию и методы фильтрации на основе контента, может привести к наиболее эффективным персонализированным рекомендациям в сфере недвижимости, включая продажу и аренду.

«Personalized Recommendations in Real Estate: A Survey»
















В статье [3] авторы Maxim Naumov, Dheevatsa Mudigere, Hao-Jun Michael Shi∗, Jianyu Huang, Narayanan Sundaraman, Jongsoo Park, Xiaodong Wang, Udit Gupta† , Carole-Jean Wu, Alisson G. Azzolini, Dmytro Dzhulgakov, Andrey Mallevich, Ilia Cherniavskii, Yinghai Lu, Raghuraman Krishnamoorthi, Ansha Yu, Volodymyr Kondratenko, Stephanie Pereira, Xianjie Chen, Wenlin Chen, Vijay Rao, Bill Jia, Liang Xiong and Misha Smelyanskiy рассматривают проблемы и возможности персонализированных рекомендаций для электронной коммерции. Они считают, что персонализированные рекомендации могут помочь покупателям быстрее найти нужный товар, что повышает удовлетворенность клиентов и увеличивает продажи. Однако, авторы также указывают на вызовы, которые возникают при реализации персонализированных рекомендаций, такие как проблемы конфиденциальности и безопасности данных, прозрачности и интерпретируемости рекомендаций, и качества данных.

Авторы статьи проводят обзор существующих методов рекомендаций для электронной коммерции, включая коллаборативную фильтрацию, фильтрацию на основе контента, гибридные методы и глубокое обучение. Они также обсуждают новые подходы, такие как использование контекста покупки, социальных данных и визуальных данных для улучшения качества рекомендаций.

Авторы подчеркивают, что для успешной реализации персонализированных рекомендаций необходимо учитывать как аспекты технической реализации, так и социальные и этические вопросы. Они также предлагают несколько направлений для дальнейших исследований, таких как разработка более точных алгоритмов рекомендаций, улучшение интерпретируемости и объяснимости рекомендаций, а также более глубокое понимание пользовательского поведения и потребностей.

Статья: "Deep Learning Recommendation Model for Personalization and Recommendation Systems ".









В статье [4] автор Judith Irene Maria de Groot рассматривает противоречия персонализации в рекламе Facebook и ее влияние на отношение к бренду.

Исследование основано на теории противоречий персонализации, которая предполагает, что хотя персонализация может улучшить эффективность рекламы, она также может вызывать отрицательные реакции у пользователей, такие как нарушение частной жизни и ощущение манипуляции.

Автор провел опрос более чем 700 пользователей Facebook и обнаружили, что персонализация рекламы имеет положительное влияние на отношение к бренду, но только если она оценивается как релевантная. В противном случае, персонализация может вызвать отрицательную реакцию.

Для более глубокого понимания влияния интрузивности рекламы на взаимосвязь между персонализацией и отношением к бренду, автор также изучил модерирующий эффект интрузивности. Исследование показало, что более интрузивная реклама снижает позитивный эффект персонализации на отношение к бренду.

Таким образом, автор приходит к выводу, что хотя персонализация может улучшить отношение к бренду, она должна быть релевантной и не должна быть слишком интрузивной.

Статья "The Personalization Paradox in Facebook Advertising: The Mediating Effect of Relevance on the Personalization–Brand Attitude Relationship and the Moderating Effect of Intrusiveness"
















В статье [5] авторы Pierfrancesco Bellini, Luciano Alessandro Ipsaro Palesi, Paolo Nesi, Gianni Pantaleo описывают разработанную ими систему рекомендаций с несколькими кластерами для розничной торговли модной одежды. 
Система рекомендаций основывается на многоуровневом подходе к кластеризации товаров и профилей пользователей в онлайн и физических магазинах.
Авторы выбрали метод K-медоидов для анализа кластеров, так как большинство полей были текстовыми описаниями, а не числами. Расстояние между элементами вычислялось с помощью расстояния Гауэра, который находится в диапазоне от 0 до 1. Оптимальное количество кластеров было определено методом силуэта и составило 13. Так же авторы использовали данные о поведении и предпочтениях пользователей для группировки их в 14 кластеров методом K-средних и методом силуэта (Silhouette). Это позволило получить наиболее точные группы, учитывающие поведение и предпочтения пользователей. Меньшее количество кластеров не подходило, так как было бы трудно делать выборки и анализы в больших группах пользователей.
Авторами было проведено два эксперимента. В первом эксперименте в период с января по июнь 2020 года учитывались сгенерированные предложения, без стимулирования покупателей. Учитывалось совпадение между предложениями и товарами, приобретенными покупателями, путем проверки транзакций и проверки экспертных продавцов. Этот анализ показал, что было получено около 10 000 предложений от 400 покупателей. По сгенерированным предложениям было приобретено 6,36% товаров. 
Чтобы стимулировать определенный класс пользователей, во втором эксперименте авторы настроили рекомендательную систему на оперативный режим с июля 2020 года по декабрь 2020 года. Этот анализ с использованием стимулированных клиентов показал, что на 67 выбранных клиентах в ходе исследования было сгенерировано 3050 предложений, тогда как только около 20% из них было фактически отправлено клиентам (в магазинах и/или по электронной почте). Среди предложенных товаров 9,84% были приобретены или протестированы. Таким образом, благодаря стимулированию системы рекомендаций, мы увеличили внимание клиентов на 3,48%.

Статья: «Multi Clustering Recommendation System for Fashion Retail» 13.01.2022






В статье [6]  авторы Barrie Kersbergen, Sebastian Schelter обсуждают разработку и улучшение рекомендательной системы. В статье приводятся два исследования, нацеленных на улучшение предиктивной производительности системы с помощью алгоритмических и системных подходов.

Авторы указывают, что система рекомендации вычисляет девять моделей: Связанные товары (Related-Products), Заказ после клика (Order-After-Click), Куплено вместе (Purchased-Together), Семейство (Family), Похожие товары (Similar), В тренде (Trending), Создатель (Creator), Бренд и издатель (Brand & Publisher). Авторы исследования включили в свой анализ восемь различных алгоритмов рекомендаций в. Из них четыре используют подходы машинного обучения на основе нейронных сетей: GRU4Rec, подход на основе RNN с функциями потерь ранжирования, NARM и STAMP. Эти алгоритмы строят рекомендации на основе последовательности действий пользователя в текущей сессии. Кроме того, авторы включили алгоритм NEXTITNET, использующий свертки для изучения короткосрочных и долгосрочных зависимостей между товарами. Также были использованы четыре метода ближайших соседей: AR (Association rules), SR (Sequential rules), а также S-KNN и VS-KNN (Session k-Nearest Neighbor). 
Во время проведения эксперимента авторы заметили, что 90-й процентиль распределения задержки ответа между сервисом предсказаний и нашим веб-магазином, работающим в ЦОД, составляет 32 мс, в то время как настройка GCP требует только 15 мс. Кроме того, они заметили увеличение важного метрического показателя, связанного с заказами, на 2,19%, а также соответствующего показателя, связанного с доходом, на 2,31%. Авторы подтвердили, что положительный эффект на метрики является статистически значимым с помощью теста хи-квадрат. В целом, они сделали вывод, что важные метрики, связанные с заказами и доходом, положительно коррелируют с уменьшением задержки ответа на 17 мс. Их результаты показывают, что пользователи более склонны совершать покупку, если рекомендации предоставляются с более низкой задержкой, при условии, что две рекомендательные системы, основанные на контенте, идентичны.

"Learning from a Retail Recommendation System on Billions of Interactions at bol.com"







В статье [7] автор Taufiq Azri описывает разработку системы рекомендаций для розничного бизнеса. Автор обсуждает, как использовать методы машинного обучения, такие как коллаборативная фильтрация и контентная фильтрация, чтобы предложить пользователям персонализированные рекомендации товаров
В статье были использованы два метода рекомендации: коллаборативная фильтрация (Collaborative Filtering, CF) и фильтрация на основе контента (Content-Based Filtering, CBF), которые были объединены в гибридный алгоритм (Hybrid Recommendation Algorithm, HRA). Таким образом, CF использовался для анализа и рекомендации товаров на основе предпочтений других пользователей, CBF использовался для анализа свойств товаров и рекомендации товаров с похожими свойствами, а HRA использовался для объединения результатов обоих методов, чтобы предоставить более точные рекомендации.
В экспериментальной части исследования использовалась база данных онлайн-ритейлера RetailRocket, содержащая информацию о действиях пользователей на сайте, таких как просмотр, добавление в корзину и покупка товаров. База данных содержала информацию за период с апреля 2015 года по апрель 2016 года. В исследовании было проведено сравнение различных алгоритмов рекомендации, включая 
SVD - Сингулярное разложение матрицы 
SVD++ - Расширенное сингулярное разложение матрицы
Item-based CF - Рекомендации на основе товаров
User-based CF - Рекомендации на основе пользователей
CBF - Рекомендации на основе контента
Hybrid - Гибридный метод рекомендации
Для оценки качества рекомендаций использовались метрики precision, recall и F1-score.
Результаты показали, что гибридный метод рекомендации, который объединяет SVD и CBF, показал наилучшие результаты по всем метрикам. При этом precision составил 0.48, recall - 0.38, а F1-score - 0.42. Эти результаты оказались лучше, чем у других алгоритмов рекомендации, таких как SVD (0.38, 0.29, 0.33) и CBF (0.36, 0.28, 0.31). Было показано, что гибридный метод позволяет улучшить качество рекомендаций, объединяя в себе преимущества двух различных подходов.


"Product Recommendation based on Shared Customer's Behaviour"



В статье [8] авторы Emre Yıldız, Ceyda Güngör Şen, Eyüp Ensar Işık предлагают интегрированную систему рекомендаций для продуктов в розничной торговле, которая объединяет различные техники обработки данных. 
Создание предложений о рекомендуемых продуктах для каждого клиента было разделено на пять этапов, и для этого использовались несколько технологий и алгоритмов. В первой фазе они использовали методологию RFM для сегментации клиентов на основе их покупательского поведения. Во второй фазе они применили алгоритм кластеризации K-means для группировки клиентов по схожим характеристикам и предпочтениям. В третьей фазе была использована ассоциативная аналитика на основе алгоритма Apriori для выявления связей между покупками клиентов. В четвертой фазе были применены стандартные методы машинного обучения для определения наиболее подходящих продуктов для каждого клиента на основе их покупательской истории. Наконец, в пятой фазе авторы использовали полученные результаты для подготовки персонализированных списков рекомендуемых продуктов для каждого клиента.
Авторы провели эксперимент на данных онлайн-магазина по продаже одежды. С помощью алгоритма ассоциативных правил были выделены кластеры покупателей с похожими потребительскими характеристиками. Затем была создана система рекомендаций для каждого кластера, которая была протестирована на выбранном случайном покупателе. С помощью трех метрик - recall, precision и F1 - была измерена эффективность системы, которая составила 0,25, 0,05 и 0,083 соответственно. Кроме того, система была протестирована на 2342 покупателях и сравнена с текущей системой RS. Результаты показали, что разработанная система более эффективна и приводит к увеличению среднего объема продаж.


«A Hyper-Personalized Product Recommendation System Focused on Customer Segmentation: An Application in the Fashion Retail Industry»











В статье [9] авторы Hyunwoo Hwangbo, Yang Sok Kim, Kyung Jin Cha представляют систему рекомендаций, реализованную в крупной корейской компании, которая продает модные товары через онлайн и офлайн магазины.
Авторы исследования описали систему рекомендаций на основе совместной фильтрации, разработанную для крупной корейской компании, занимающейся продажей модной одежды через онлайн и оффлайн торговые площадки. Для подготовки данных система генерирует список продуктов, метаданные продуктов, данные истории покупок (оффлайн) и данные истории кликов (онлайн). Система также применяет функцию снижения предпочтений для учета изменений предпочтений покупателей во времени и рекомендует заменительные и дополнительные продукты, используя информацию о категориях продуктов.
Авторы использовали ORACLE PL/SQL для разработки рекомендательной системы K-RecSys. Для сбора данных о покупках были использованы системы управления магазином и онлайн-магазином, а также Enterprise Data Warehouse (EDW) и Web Log. Система генерирует два набора рекомендаций - для замены и для дополнения - на основе данных о покупках и просмотрах товаров, а также метаданных о продуктах. Рекомендации копируются в репозиторий онлайн-магазина и обновляются ежедневно с помощью Informatica Workflow Manager.
Для эксперимента K-RecSys была реализована в онлайн-магазине Company K в дополнение к уже существующей системе рекомендаций. Был проведен A / B-тест в течение трех недель, чтобы сравнить производительность K-RecSys с существующей системой рекомендаций.  Всего было сделано 7476 покупок, причем 50.1% были совершены группой эксперимента, а 49.9% - контрольной группой. Результаты показали, что процент покупок, сделанных через рекомендации группы эксперимента, немного выше, чем контрольной группы (12.3% против 8.9%). Так же что K-RecSys предоставляет более эффективные рекомендации, и что рекомендации на замену продуктов чаще получают клики, чем рекомендации на дополнительные продукты.


«Recommendation system development for fashion retail e-commerce»
