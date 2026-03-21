const users = [
  { username: "admin", password: "1234" },
  { username: "nikita", password: "qwerty" }
];

function verifyUser(username, password) {
  const user = users.find(u => u.username === username);

  if (!user) {
    return "Пользователь не найден";
  }

  if (user.password !== password) {
    return "Неверный пароль";
  }

  return "Успешный вход ✅";
}
