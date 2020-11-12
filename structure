//structure pour la gestion des troupeau

typedef struct Date
{
char jour[10];
char mois[15];
int annee;

}Date;

typedef struct troupeau
{
 int idtroupeau;
 int genre // type boolean: 0->femelle ; 1->male
 int type // type boolean 0->brebi ; 1->vau
 Date date;
}troupeau;

//structure pour la marque ayant le maximum de capteur
enum marque { };

typedef struct capteur
{
int idcapteur;
char nomcapeteur[15];
marque mcapteur;
int valeur;
}capteur;
//prototype des fonctions

void ajoutertroupeau();
void supprimertroupeau();
void modifiertroupeau();
void afficherListetroupeau();

