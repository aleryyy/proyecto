
#include <iostream>	
using namespace std;

int main() {
	int opcion, i = 0, salir = 0, cant;
	char nomp[100], hora[100], nomt[100], desc[100], preut[100], precun[100];
	do {
		cout << "BIENVENIDO, ELIGE UNA OPCION" << endl;
		cout << "1. Agendar cita" << endl << "2. Modificar cita" << endl << "3. Eliminar cita" << endl << "4. Lista de citas vigentes" << endl << "5. Limpiar pantalla" << endl << "6. Salir" << endl;
		cin >> opcion;
		switch (opcion) {
		case 1:
			do {
				cout << "Nombre del paciente:" << endl;
				cin >> nomp;
				cout << "Hora del tratamiento:" << endl;
				cin >> hora;
				cout << "Nombre del tratamiento:" << endl;
				cin >> nomt;
				cout << "Descripcion:" << endl;
				cin >> desc;
				cout << "Precio unitario del tratamiento:" << endl;
				cin >> preut;
				cout << "Cantidad del tratamiento:" << endl;
				cin >> cant;
				cout << "Precio unitario:" << endl;
				cin >> precun;
				cout << "¿Desea regresar al menu? " << endl << "1. Si" << endl << "2.No" << endl;
				cin >> salir;
			} while (salir ==1);
			break;
		case 2:
			break;

		case 3:
			break;

		case 4:
			break;

		case 5:
			break;

		case 6:
			exit(1);
			break;
		default:
			cout << "Ingresa una opcion valida";
		}
		cout << "¿Desea regresar al menu? " << endl << "1. Si" << endl << "2.No" << endl;
		cin >> salir;
	} while (salir == 1);
}
