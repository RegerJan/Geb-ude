# Gebeude
In diesem Repository geht es um Vererbung

# Oberklasse Gebäude

Das ist die Oberklasse aller Folgenden Datein.


    public class Gebaeude
    {
      protected double hoehe;

      protected int besucher;

      public Gebaeude( double pHoehe, int pBesucher )
      {
          hoehe = pHoehe;
          besucher = pBesucher;
      }

      public double getHoehe()
      {
          return hoehe;
      }

      public int anzahlBesucher() {
          return besucher;
      }

    }
