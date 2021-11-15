# BSI_realizacja_SWE4_BP-3_BP-4_BP-7 by Anastasiia Ponkratova, Julia Migiel
## Raport z testowania modułów
Zgodnie z raportem pokrycia testowego wygenerowanym przez narzędzie JUnit, pokrycie wynosi 95%, ponieważ jedyna klasa main nie zawiera żadnych zmiennych ani metod. Pełna statystyka jest przedstawiona w poniższym raporcie:

![alt text](https://github.com/s20488/BSI_realizacja_SWE4_BP-3_BP-4_BP-7/blob/main/test_coverage.png?raw=true)

#### test_should_check_if_data_is_properly_filtered()
        Test sprawdza, czy dane są poprawnie filtrowane według przedziałów wieku, dochodu i płci oraz porównuje wyniki z bieżącą             stroną i jej wielkością
        **setAgeFrom** - ustawia początkowy zakres wieku
        **setAgeTo** - ustawia ostateczny zakres wieku
        **setIncomeFrom** - ustawia początkowy zakres dochodu 
        **setPage** - ustawia numer i rozmiar strony
        **getSelectedGenders** - ustawianie płci
        **getCurrentPage** - ustawia aktualną stronę
        **getPages** - uzyskuje numer i rozmiar strony
        **getItems** - pobieranie zawartości listy
        **assertThat** - konstrukt sprawdzający założenia dotyczące wartości dowolnych danych
        
#### test_should_check_if_paging_works()


#### test_should_check_if_search_by_name_works()

#### test_should_check_if_search_by_age_works()

#### test_should_check_if_search_by_gender_works()

#### test_should_check_if_search_by_income_works()
