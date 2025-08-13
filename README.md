# Strategia-optymalizacji-cenowej-dla-nowych-obiekt-w-Airbnb
Analiza danych Airbnb, aby zrozumieć, które czynniki najbardziej wpływają na ceny wynajmu i propozycja strategii, które pomogą nowym gospodarzom ustalić konkurencyjne ceny swoich ofert.
 	Najważniejsze obserwacje:
  
 	Typy pokoju:
  
 	Najwięcej ofert to:
  
Entire home/apt — 53 701 ofert (~52%)

Private room — 46 556 ofert (~45%)

Shared room — tylko 2 226 ofert

Hotel room — marginalna liczba (116 ofert)

 	Co ciekawe, średnia cena w każdym rodzaju obiektu noclegowego jest bardzo podobna 
 	ok. 625–668 USD.
Lokalizacja (neighborhood group):

 	Najwięcej ofert znajduje się w:
  
Manhattan — 43 821 ofert

Brooklyn — 41 842 ofert

Queens — 13 267 ofert

Bronx i Staten Island mają marginalne znaczenie.

 	Ceny w dzielnicach są podobne, na wykresach różnice są prawie nie widoczne, dlatego nie uwzględniłam ich na moim dashboardzie. 
 	Mediany między 580–630 USD
  
Dostępność 365 dni w roku

 	Dostępność:
 	Średnia dostępność to ~140 dni w roku, mediana to 96 dni.
  
 	Jest to sygnał, aby zwrócić szczególną uwagę na elastyczność przy proponowaniu noclegów. Możemy zyskać dodatkowe rezerwację, jeśli nasz obiekt będzie dostępny przez większą część roku – gdzie u konkurencji niekoniecznie. 
  
Liczba recenzji a doświadczenie hosta

 	Zbiorczo potraktowałam trzy kolumny: number_of_reviews, calculated_host_listings_count oraz host_identity_verified jako składowe doświadczenie właściciela. Utworzyłam nową koulmnę: host_experience_score, gdzie następnie zbadałam wpływ doświadczenia na liczbę recenzji. Z mojego wykresu wynika, że bardziej doświadczeni właściciele zdają sobie sprawę jak istotne w dzisiejszym świecie są opinie w Internecie i mogą się pochwalić wyższą liczbą ocen niż ich mniej doświadczeni koledzy. Wpływ na to może mieć zarówno lepsza obsługa jak i na przykład ulotki z kodem QR do zostawienia oceny dołączane do rachunku.
  

Wnioski i rekomendacje

 	1. Jeśli jesteś początkującym hostem i dopiero zaczynasz swoją przygodę z wynajmem obiektów dla turystów, najbezpieczniejsza opcja to prywatna kwatera (pokój lub mieszkanie) w dzielnicy Brooklyn lub Manhatann. Na taki typ obiektu oraz lokalizację na pewno znajdą się chętni, chociaż trzeba mieć też na uwadze dużą konkurencję. 
  
 	2. Najmniejszym zainteresowaniem cieszą się shared room – pokoje współdzielone. W obecnych czasach, ludzie chętniej wydadzą więcej ale na miejsce, gdzie będą doświadczać odrobiny prywatności, niż mniej, ale współdzielenie z obcymi osobami. Świadczy też o tym mniejsza liczba ocen i wyświetleń takich ofert.

