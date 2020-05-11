# PRAP2

import  androidx.annotation.NonNull ;
import  androidx.annotation.Nullable ;
importar  androidx.room.ColumnInfo ;
importar  androidx.room.Entity ;
importar  androidx.room.PrimaryKey ;

@Entidade
@Entity ( tableName  =  " things " ) // criação da entidade

 classe  pública things {
	
	@PrimaryKey ( autoGenerate  =  true )
	@NonNull
	@ColumnInfo ( name  =  " thingsId " )
	private  int mld;

	@Nullable
	@ColumnInfo ( name  =  " CreationDate " )
	// String privada mCreationDate

@Nullable
	@ColumnInfo ( name  =  " Description " )
	private  String mDescription;
	
	@Nullable
	@ColumnInfo ( name  =  " Age " )
	private  int mAge;

@Nullable
	@ColumnInfo ( nome  =  " Grade " )
	private  int mGrade;
	
pública  Things ( @Nullable  de Cordas  Data de criação , Cordas  Nome , Cordas  Age , int  Grade ) {
mCreationDate =  Data de criação ;
mDescription =  Description ;
mAge = age;
mGrade =  grade ;
	}

	// Gerando getters e setters
	
	public  int  getId () {
		return mID;
	}

	público  vazio  setId ( int  mId ) {
		Mid =  id ;
	}

	public  String  getCreationDate () {
		return mCreationDate;
	}

	public  void  setmCreationDate ( String  CreationDate ) {
		mCreationDate =  CreationDate ;
	}

	public  String  getDescription() {
		return mDescription;
	}

	público  vazio  setnsetDescription(Descrição  da string  ) {
		mName =  Descrição  ;
	}

	public  String  getAge () {
		retornar mAge;
	}

	public  void  setAge ( String  Age ) {
		mAge =  Age ;
	

	public  int getGrade() {
		retorno mGrade;
	}

	public  void setGrade ( int mGrade) {
		mGrade =  Grade ;
	} 
	
private  int mGrade; 

private  String mCreationDate;

}
