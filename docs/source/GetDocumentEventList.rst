﻿GetDocumentEventList
====================

Метод объекта :doc:`Organization <Organization>`

**Синтаксис**


GetDocumentEventList(<EventId>)

**Параметры**


-  <EventId> (cтрока, обязательный) идентификатор последнего полученного
   события.

**Возвращаемое значение**


Коллекция :doc:`Collection <Collection>` объектов
:doc:`DocumentEvent <DocumentEvent>`.

**Описание**


Возвращает список событий, следующих за событием с идентификатором
EventId в хронологическом порядке. При этом само событие с
идентификатором EventId в этот список не включается.
