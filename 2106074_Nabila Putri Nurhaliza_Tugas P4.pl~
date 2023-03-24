suami(david, amy).
suami(jack, karen).
suami(john, susan).

orangtua(david, liza).
orangtua(david,john).
orangtua(jack, susan).
orangtua(jack, ray).
orangtua(john, peter).
orangtua(john, mary).

is_suami(X,Y) :- suami(X,Y).
is_istri(Y,X) :- suami(X,Y).
is_anak(Z,Y) :- is_istri(Y,X), orangtua(X,Z).
is_sodara(Y,Z) :- orangtua(X,Y), orangtua(X,Z).
is_ibu(X,Z) :- orangtua(Y,Z), suami(Y,X).
