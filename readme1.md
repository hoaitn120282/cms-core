#Naming convention:

  ##Classes, enums, typedefs, và extensions nên được đặt tên với ký tự đầu mỗi từ được viết hoa: Ex: UpperCamelCase

*class MainScreen { ... }
*enum MainItem { .. }
*typedef Predicate<T> = bool Function(T value);
*extension MyList<T> on List<T> { ... }

  ##Libraries, packages, directories, và source files thì nên viết thường và có dấu gạch dưới giữa 2 tuwf: Ex: lowercase_with_underscores

*library firebase_dynamic_links;
*import 'socket/socket_manager.dart';
  ##Variables, constants, parameters, và named parameters sẽ tương tự như Class nhưng ký tự đầu tiên sẽ viết thường : Ex: lowerCamelCase

var item;
const bookPrice = 3.14;
final urlScheme = RegExp('^([a-z]+):');
void sum(int bookPrice) {
  // ...
}
