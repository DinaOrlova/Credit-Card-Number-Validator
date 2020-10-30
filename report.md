# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

30.10.2020 было проведено функциональное тестирование программы Credit Card Number Validator.

На тестирование затрачено: 20 минут

В результате тестирования выявлены следующие дефекты:
* https://github.com/DinaOrlova/lec-1.1-zadacha-2/issues/1
* https://github.com/DinaOrlova/lec-1.1-zadacha-2/issues/2
* https://github.com/DinaOrlova/lec-1.1-zadacha-2/issues/3
* https://github.com/DinaOrlova/lec-1.1-zadacha-2/issues/4
* https://github.com/DinaOrlova/lec-1.1-zadacha-2/issues/5
* https://github.com/DinaOrlova/lec-1.1-zadacha-2/issues/6

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорты (ссылки даны в разделе результатов тестирования).

В качестве тестовых данных использовались сгенерированные валидные номера карт с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html:

**1. VISA:**
* 4330437701270826
* 4929388162422211751

**2. MasterCard:**
* 5279272973391285

**3. American Express (AMEX):**
* 370100035651298

**4. Discover:**
* 6011155628973717
* 6011058778309232851

**5. JCB:**
* 3540834682880334
* 3542221641249363377

**6. Diners Club - North America:**
* 5505337680055659

**7. Diners Club - Carte Blanche:**
* 30047426349135

**8. Diners Club - International:**
* 36847256488984

**9. Maestro:**
* 6304532061048999

**10. Visa Electron:**
* 4913632842710038

**11. InstaPayment:**
* 6383740169632226

Тестирование производилось в следующем окружении:
- Windows 10 Pro х64
- Оpenjdk version "11.0.9" 2020-10-20
- JetBrains Toolbox version 1.18.7455.0
