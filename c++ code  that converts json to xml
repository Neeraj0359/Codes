#include <iostream>
#include "include/picojson.h";
#include "include/pugixml.hpp";
using namespace std;

int main() {
   
    const char* json =
        "{\"menu\": {"
        "\"id\": \"f\","
        "\"popup\": {"
        "  \"menuitem\": ["
        "    {\"v\": \"0\"},"
        "    {\"v\": \"1\"},"
        "    {\"v\": \"2\"}"
        "   ]"
        "  }"
        "}"
        "}";
    picojson::value v;
    std::string err;
    const char* json_end = picojson::parse(v, json, json + strlen(json), &err);
    
}
