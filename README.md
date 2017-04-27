# withoutEnd
public String withoutEnd(String str) {
  if (str.length() <= 2){
    return "";
  }
  else{
    return str.substring(1, str.length()-1);
  }
}
