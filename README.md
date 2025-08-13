# Strategia-optymalizacji-cenowej-dla-nowych-obiekt-w-Airbnb
Analiza danych Airbnb, aby zrozumieć, które czynniki najbardziej wpływają na ceny wynajmu i propozycja strategii, które pomogą nowym gospodarzom ustalić konkurencyjne ceny swoich ofert.
Najważniejsze obserwacje dostarczonego zbioru danych: <img width="2344" height="210" alt="image" src="https://github.com/user-attachments/assets/00f72994-a0c9-4197-8967-3402af1c9f96" />
Typy pokoju:
Najwięcej ofert to:
Entire home/apt — 53 701 ofert (~52%)
Private room — 46 556 ofert (~45%)
Shared room — tylko 2 226 ofert
Hotel room — marginalna liczba (116 ofert)
Co ciekawe, średnia cena w każdym rodzaju obiektu noclegowego jest bardzo podobna 
ok. 625–668 USD.
<img width="1522" height="523" alt="image" src="https://github.com/user-attachments/assets/59b2a225-f9d9-410b-b78f-3b3d66b8ee62" />
Lokalizacja (neighborhood group):<img width="1424" height="210" alt="image" src="https://github.com/user-attachments/assets/b17d8400-1faf-48c9-bbcd-808b0c6e222f" />
Najwięcej ofert znajduje się w:
Manhattan — 43 821 ofert
Brooklyn — 41 842 ofert
Queens — 13 267 ofert
Bronx i Staten Island mają marginalne znaczenie.
Ceny w dzielnicach są podobne, na wykresach różnice są prawie nie widoczne, dlatego nie uwzględniłam ich na moim dashboardzie. 
Mediany między 580–630 USD
<img width="2283" height="448" alt="image" src="https://github.com/user-attachments/assets/ca878b5c-8382-4630-a203-62524ca8d488" />
Dostępność 365 dni w roku <img width="1204" height="210" alt="image" src="https://github.com/user-attachments/assets/79f8c5df-4dda-4198-a79f-96ca06d27724" />
Dostępność:
Średnia dostępność to ~140 dni w roku, mediana to 96 dni.
Jest to sygnał, aby zwrócić szczególną uwagę na elastyczność przy proponowaniu noclegów. Możemy zyskać dodatkowe rezerwację, jeśli nasz obiekt będzie dostępny przez większą część roku – gdzie u konkurencji niekoniecznie. 
<img width="3866" height="236" alt="image" src="https://github.com/user-attachments/assets/0102e32f-fab1-4b61-abb8-9566b54a180c" />
Liczba recenzji a doświadczenie hosta<img width="1583" height="210" alt="image" src="https://github.com/user-attachments/assets/01392069-c9f4-47a6-a2fe-dd897d31e8c8" />
Zbiorczo potraktowałam trzy kolumny: number_of_reviews, calculated_host_listings_count oraz host_identity_verified jako składowe doświadczenie właściciela. Utworzyłam nową koulmnę: host_experience_score, gdzie następnie zbadałam wpływ doświadczenia na liczbę recenzji. Z mojego wykresu wynika, że bardziej doświadczeni właściciele zdają sobie sprawę jak istotne w dzisiejszym świecie są opinie w Internecie i mogą się pochwalić wyższą liczbą ocen niż ich mniej doświadczeni koledzy. Wpływ na to może mieć zarówno lepsza obsługa jak i na przykład ulotki z kodem QR do zostawienia oceny dołączane do rachunku. 
<img width="10615" height="88" alt="image" src="https://github.com/user-attachments/assets/9ffd0b02-f3d3-4203-866a-5978245994bf" />
Wnioski i rekomendacje <img width="1072" height="210" alt="image" src="https://github.com/user-attachments/assets/64760b76-e2a7-43ed-9514-2712ab6cb7db" />
1. Jeśli jesteś początkującym hostem i dopiero zaczynasz swoją przygodę z wynajmem obiektów dla turystów, najbezpieczniejsza opcja to prywatna kwatera (pokój lub mieszkanie) w dzielnicy Brooklyn lub Manhatann. Na taki typ obiektu oraz lokalizację na pewno znajdą się chętni, chociaż trzeba mieć też na uwadze dużą konkurencję. 
2. Najmniejszym zainteresowaniem cieszą się shared room – pokoje współdzielone. W obecnych czasach, ludzie chętniej wydadzą więcej ale na miejsce, gdzie będą doświadczać odrobiny prywatności, niż mniej, ale współdzielenie z obcymi osobami. Świadczy też o tym mniejsza liczba ocen i wyświetleń takich ofert<img width="5677" height="162" alt="image" src="https://github.com/user-attachments/assets/9ecfa61b-f899-4116-8ede-8f06ac4483c4" />
