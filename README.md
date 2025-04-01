#include <iostream>
#include <string>

using namespace std;

int main() {
    int eleccion;
    int intentos = 0;
    
    // Escenario inicial
    cout << "Estás en la barra con un vaso en la mano. Algunos de tus amigos están alrededor de ti, pero te das cuenta de que uno de ellos está conversando con una chica que te parece interesante." << endl;
    cout << "Decides qué hacer." << endl;

    // Bucle principal del juego
    while (true) {
        cout << "\nOpciones:" << endl;
        cout << "1. Tomar otro trago" << endl;
        cout << "2. Dejar de tomar" << endl;
        cout << "3. Ir a bailar" << endl;
        cout << "Elige una opción (1-3): ";
        cin >> eleccion;

        if (eleccion == 1) {
            // Tomar otro trago
            cout << "Tu amigo te ofrece otro vaso. Aunque ya has tomado algo, decides no rechazarlo." << endl;
            while (true) {
                cout << "\nOpciones:" << endl;
                cout << "1. Sí, uno más no hace daño" << endl;
                cout << "2. No, ya basta por hoy" << endl;
                cout << "3. Ir a la pista de baile" << endl;
                cout << "Elige una opción (1-3): ";
                cin >> eleccion;

                if (eleccion == 1) {
                    // Tomar otro trago
                    cout << "Has tomado varios tragos en poco tiempo. Te sientes mareado, pero decides seguir." << endl;
                    intentos = 0;  // Reiniciar los intentos
                    while (true) {
                        cout << "\nOpciones:" << endl;
                        cout << "1. Sí, más tarde me recupero" << endl;
                        cout << "2. Ya no, voy a descansar un poco" << endl;
                        cout << "3. Ir a la pista de baile" << endl;
                        cout << "Elige una opción (1-3): ";
                        cin >> eleccion;

                        if (eleccion == 1) {
                            // Más tarde me recupero
                            cout << "Decides seguir bebiendo, pero la noche se complica..." << endl;
                            cout << "Final C - El Choque de egos" << endl;
                            return 0;
                        } else if (eleccion == 2) {
                            // Descansar un poco
                            cout << "Decides descansar un poco y tomar un respiro. La fiesta sigue." << endl;
                            cout << "Final D - La fiesta sigue" << endl;
                            return 0;
                        } else {
                            // Ir a bailar
                            cout << "Te diriges hacia la pista de baile y te olvidas de todo." << endl;
                            cout << "Final D - La fiesta sigue" << endl;
                            return 0;
                        }
                    }
                } else if (eleccion == 2) {
                    // Dejar de tomar
                    cout << "Decides dejar el vaso en la barra y alejarte de la zona de bebidas." << endl;
                    intentos = 0;  // Reiniciar los intentos
                    while (true) {
                        cout << "\nOpciones:" << endl;
                        cout << "1. Te unes a la conversación" << endl;
                        cout << "2. Vas a bailar" << endl;
                        cout << "3. Observas desde lejos" << endl;
                        cout << "Elige una opción (1-3): ";
                        cin >> eleccion;

                        if (eleccion == 1) {
                            // Unirse a la conversación
                            cout << "Te unes a la conversación con la chica. Ella parece interesada en ti." << endl;
                            cout << "Final A - Conquista inesperada" << endl;
                            return 0;
                        } else if (eleccion == 2) {
                            // Ir a bailar
                            cout << "Te diriges hacia la pista de baile, disfrutando de la fiesta." << endl;
                            cout << "Final D - La fiesta sigue" << endl;
                            return 0;
                        } else {
                            // Observar desde lejos
                            cout << "Decides observar la situación desde lejos y ves cómo tu amigo se acerca a la chica." << endl;
                            cout << "Final B - La Amistad primero" << endl;
                            return 0;
                        }
                    }
                } else {
                    // Ir a bailar
                    cout << "Te diriges hacia la pista de baile, disfrutando del ritmo de la música." << endl;
                    intentos = 0;  // Reiniciar los intentos
                    while (true) {
                        cout << "\nOpciones:" << endl;
                        cout << "1. La invitas a bailar contigo" << endl;
                        cout << "2. Te quedas bailando solo" << endl;
                        cout << "3. Vas a buscar a tu amigo" << endl;
                        cout << "Elige una opción (1-3): ";
                        cin >> eleccion;

                        if (eleccion == 1) {
                            // Invitarla a bailar
                            cout << "Te acercas a ella con confianza y la invitas a bailar. Ella acepta." << endl;
                            cout << "Final A - Conquista inesperada" << endl;
                            return 0;
                        } else if (eleccion == 2) {
                            // Quedarse bailando
                            cout << "Sigues bailando solo y disfrutas del momento." << endl;
                            cout << "Final D - La fiesta sigue" << endl;
                            return 0;
                        } else {
                            // Buscar al amigo
                            cout << "Vas a buscar a tu amigo y decides seguir la fiesta con él." << endl;
                            cout << "Final B - La Amistad primero" << endl;
                            return 0;
                        }
                    }
                }
            }
        } else if (eleccion == 2) {
            // Dejar de tomar
            cout << "Decides dejar el vaso en la barra y alejarte de la zona de bebidas." << endl;
            intentos = 0;  // Reiniciar los intentos
            while (true) {
                cout << "\nOpciones:" << endl;
                cout << "1. Te unes a la conversación" << endl;
                cout << "2. Vas a bailar" << endl;
                cout << "3. Observas desde lejos" << endl;
                cout << "Elige una opción (1-3): ";
                cin >> eleccion;

                if (eleccion == 1) {
                    // Unirse a la conversación
                    cout << "Te unes a la conversación con la chica. Ella parece interesada en ti." << endl;
                    cout << "Final A - Conquista inesperada" << endl;
                    return 0;
                } else if (eleccion == 2) {
                    // Ir a bailar
                    cout << "Te diriges hacia la pista de baile, disfrutando de la fiesta." << endl;
                    cout << "Final D - La fiesta sigue" << endl;
                    return 0;
                } else {
                    // Observar desde lejos
                    cout << "Decides observar la situación desde lejos y ves cómo tu amigo se acerca a la chica." << endl;
                    cout << "Final B - La Amistad primero" << endl;
                    return 0;
                }
            }
        } else {
            // Ir a bailar
            cout << "Te diriges hacia la pista de baile, disfrutando del ritmo de la música." << endl;
            intentos = 0;  // Reiniciar los intentos
            while (true) {
                cout << "\nOpciones:" << endl;
                cout << "1. La invitas a bailar contigo" << endl;
                cout << "2. Te quedas bailando solo" << endl;
                cout << "3. Vas a buscar a tu amigo" << endl;
                cout << "Elige una opción (1-3): ";
                cin >> eleccion;

                if (eleccion == 1) {
                    // Invitarla a bailar
                    cout << "Te acercas a ella con confianza y la invitas a bailar. Ella acepta." << endl;
                    cout << "Final A - Conquista inesperada" << endl;
                    return 0;
                } else if (eleccion == 2) {
                    // Quedarse bailando
                    cout << "Sigues bailando solo y disfrutas del momento." << endl;
                    cout << "Final D - La fiesta sigue" << endl;
                    return 0;
                } else {
                    // Buscar al amigo
                    cout << "Vas a buscar a tu amigo y decides seguir la fiesta con él." << endl;
                    cout << "Final B - La Amistad primero" << endl;
                    return 0;
                }
            }
        }
    }

    return 0;
}
