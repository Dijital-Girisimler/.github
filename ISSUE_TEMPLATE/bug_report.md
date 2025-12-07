name: "🐞 Bug Report"

description: Bir hata tespit ettiysen buradan bildirebilirsin.

title: "\[BUG] "

labels: \["bug"]

body:

&nbsp; - type: textarea

&nbsp;   id: description

&nbsp;   attributes:

&nbsp;     label: Sorunun Açıklaması

&nbsp;     description: Ne oldu, nasıl oldu?

&nbsp;   validations:

&nbsp;     required: true

&nbsp; - type: textarea

&nbsp;   id: steps

&nbsp;   attributes:

&nbsp;     label: Adım Adım Tekrar Etme

&nbsp;     description: Hatanın oluştuğu adımları yaz.

&nbsp; - type: textarea

&nbsp;   id: expected

&nbsp;   attributes:

&nbsp;     label: Beklenen Davranış

&nbsp; - type: textarea

&nbsp;   id: context

&nbsp;   attributes:

&nbsp;     label: Ek Bilgi



