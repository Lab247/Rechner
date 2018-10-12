unit Unit1;

{$mode objfpc}{$H+}

interface

uses
  Classes, SysUtils, FileUtil, Forms, Controls, Graphics, Dialogs, ExtCtrls,
  StdCtrls;

type

  { TfrmMain }

  TfrmMain = class(TForm)
    btnAddition: TButton;
    btnSubtraktion: TButton;
    btnMultiplikation: TButton;
    btnDivision: TButton;
    btnClose: TButton;
    edtErgebnis: TEdit;
    edtWert1: TEdit;
    edtWert2: TEdit;
    lblErgebnis: TLabel;
    lblWert1: TLabel;
    lblWert2: TLabel;
    procedure btnAdditionClick(Sender: TObject);
    procedure btnCloseClick(Sender: TObject);
    procedure btnDivisionClick(Sender: TObject);
    procedure btnMultiplikationClick(Sender: TObject);
    procedure btnSubtraktionClick(Sender: TObject);
  private
    { private declarations }
  public
    { public declarations }
  end;

var
  frmMain: TfrmMain;
  var Wert1, Wert2, Ergebnis : real;

implementation

{$R *.lfm}

{ TfrmMain }

procedure TfrmMain.btnAdditionClick(Sender: TObject);
  begin
     Wert1:= StrToFloat (edtWert1.Text);
     Wert2:= StrToFloat (edtWert2.Text);
     Ergebnis := Wert1 + Wert2;
     edtErgebnis.Text := FloatToStr(Ergebnis);
  end;

procedure TfrmMain.btnCloseClick(Sender: TObject);
begin
  close;
end;

procedure TfrmMain.btnDivisionClick(Sender: TObject);
begin
     Wert1:= StrToFloat (edtWert1.Text);
     Wert2:= StrToFloat (edtWert2.Text);
     Ergebnis := Wert1 / Wert2;
     edtErgebnis.Text := FloatToStr(Ergebnis);
end;

procedure TfrmMain.btnMultiplikationClick(Sender: TObject);
begin
     Wert1:= StrToFloat (edtWert1.Text);
     Wert2:= StrToFloat (edtWert2.Text);
     Ergebnis := Wert1 * Wert2;
     edtErgebnis.Text := FloatToStr(Ergebnis);
end;

procedure TfrmMain.btnSubtraktionClick(Sender: TObject);
begin
     Wert1:= StrToFloat (edtWert1.Text);
     Wert2:= StrToFloat (edtWert2.Text);
     Ergebnis := Wert1 - Wert2;
     edtErgebnis.Text := FloatToStr(Ergebnis);
end;

end.

